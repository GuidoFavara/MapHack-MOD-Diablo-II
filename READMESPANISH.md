TODO: Mejorar la resolución de las imagenes, subir gifs en funcionamiento, guía de compilación.

Estuve realizando algunas mejoras al MapHack Open Source de [Slash Diablo](https://github.com/planqi/slashdiablo-maphack) que creo yo estarían buenas para todos los users, esta version viene a implementar mejoras y ayudas al usuario principalmente a la hora de jugar torneos y PVP

Estas implementaciones fueron inicialmente pensadas para aplicar en el servidor [Ombu Diablo II](https://foros.ombuserver.com.ar/viewtopic.php?f=3&t=254), sin embargo al poner el source podría aplicar a cualquiera, solamente habría que cambiar los nombres de archivos puntuales

Ya no se utiliza mas el UI.Dll ahora todo va en Ombu_Settings.cfg para edicón sencilla (el ui.dll que cada uno tiene puede ser copiado dentro de éste nuevo archivo).

Detallo algunas de las mejoras:
*"Spam" que indica donde hacer click en el juego para realizar las donaciones al servidor.

*Valor de cada item aproximado según la lista de precios actual realizada por los usuarios (no oficial). El MH al entrar a una partida notifica que los precios son a modo de REFERENCIA no para ser tomados tal cual (para evitar problemas).

*Indica que items necesitas para craftear.

*Indica que items necesitas para upgradear el item en cuestión.

*Indica que RW's se pueden armar en la base.

*Indica que items necesitas para subir la runa.

*No se ven las orejas (item que indica que mataste a un jugador).

*Se incluye traduccion a español de varias opciones provistas por Slash.

Mejoras y ayudas en PVP:
*Plantilla de tablas mejoradas con recomendaciones (útil para usuarios novatos), indica cuantas resistencias son "aceptables" y permitidas según las reglas del server, los breaks y mucho mas. También te lo calcula al momento, si sumas resis te dice cuanta te falta para tener lo "ideal".

*Modo Arbitro: Lo mejor de todo

*Indica cuando un usuario utiliza pociones de Vida o Mana, usa Auras no permitidas o Usa Templos.
Para que esto funcione NO es necesario que todos tengan el MH actualizado un user con MH viejo puede ser detectado por un user con el MH nuevo, esto se debe a que se interceptan los packets envviados al server y se devuelve en formato texto (notificación).



*La notificación le aparece a todo usuario que posea mi version del MH.

*Los usuarios no necesitan estar "cerca" para que esta notificación aparezca, quiere decir que mientras ambos esten en el acto 1 va a figurar que potearon o hicieron algo no permitido.

*Tiene un activador para evitar el flood a quien no le guste o sobre todo si se usa en bh no te aparezca una notificación molesta e inútil para ese ámbito

Se pueden buscar los cambios realizados (CTRL+F) en la solución escribiendo mi nombre (guido) esta todo comentado.

TODO:
Me gustaría implementar contador de tiempo restante en buffs

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/1.jpg?raw=true)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Notificaciones.jpg?raw=true)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Tablas.jpg?raw=true)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Atajos.jpg?raw=true)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Valor-Items.jpg)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Craft.jpg)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Upgrade-2.jpg)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/RW.jpg)

![atext](https://github.com/GuidoFavara/MapHack-MOD-Diablo-II/blob/master/Pictures/Runas.jpg)
