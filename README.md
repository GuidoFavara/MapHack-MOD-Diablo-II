Necesito hacer el readme agradable a la lectura y implementar traduccion al ingles, linkear las fotos viejas y nuevas.

Aclaración GameTag: Dubai/Emirati
Servidor para el cual fue pensado: https://foros.ombuserver.com.ar/viewtopic.php?f=3&t=254

Estuve realizando algunas mejoras al MH que creo yo estarían buenas para todos los users, esta version NO viene a mejorar al que le anda mal o lo lagea el MH, sino a implementar mejoras y ayudas al usuario.

Ya no se usa mas el UI.Dll ahora todo va en Ombu_Settings.cfg (el ui.dll que cada uno tiene puede ser copiado dentro de éste nuevo archivo).

Detallo algunas de las mejoras:

*"Spam" que indica la url para realizar las donaciones al servidor.
*Valor de cada item aproximado según la lista de precios actual realizada por los usuarios (no oficial). El MH al entrar a una partida te dice que los precios son a modo de REFERENCIA no para ser tomados tal cual (para evitar problemas)
*Indica que items necesitas para craftear.
*Indica que items necesitas para upgradear el item en cuestión.
*Indica que RW's se pueden armar en la base
*Indica que items necesitas para subir la runa
*No se ven las orejas

Y lo mas importante. Mejoras en PVP

*Plantilla de tablas mejoradas con recomendaciones (útil para usuarios novatos), indica cuantas resis son "aceptables" y permitidas, los braks y mucho mas. También te lo calcula al momento si sumas resis te dice cuanta te falta para tener lo "ideal".

*Modo Arbitro: Lo mejor de todo

*Indica cuando un usuario utiliza pociones de Vida o Mana, usa Auras no permitidas o Usa Templos.

*Para que esto funcione no es necesario que todos tengan el MH actualizado un user con MH viejo puede ser detectado por un user con el MH nuevo.

*La notificación le aparece a todo usuario que posea el MH nuevo.

*Los usuarios no necesitan estar "cerca" para que esta notificación aparezca, quiere decir que mientras ambos esten en el acto 1 va a figurar que potearon o hicieron algo no permitido.

*Tiene un activador para evitar el flood a quien no le guste o sobre todo si se usa en bh no te aparezca una notificación molesta e inútil para ese ámbito

Iniciar con BH.sln
Compilar en Packaging > Win32 
el dll sale en la carpeta "Packaging"

Del paquete eliminé el inyector ya que no lo utilizamos.

Arhivos modificados hasta donde recuerdo: (debí usar git).
UI.cpp solo traducciones y movi el menu del mapa asi esta mas prolijo (esto no esta marcado no me acuerdo donde lo toque pero era aca)
StatsDisplay.cpp Modificado casi integro agrega breaks a la tabla, traduzco el resto
ScreenInfo.cpp Modifico que la ventana del D2 tenga el nombre del server, agrego donaciones, mh Dubai 
Mapchack.cpp Traduzco opciones y agrego mas al panel, modo arbitro, notificacion de habilidades
Itemmover.cpp traducciones
Item.cpp desactivo opciones que no quice modificar sistema de ping para una variable en el mh que te muestre segun tu filtro los items, agrego alertas, mensaje al inicio de la partida
BH.cpp aca traduzco y paso todo a ombu_settings.cfg
AutoTele.cpp: traducciones

TODO:
D2Helpers.cpp CREO que por aca anda el tema de las trampas en el mapa probe mucho sin exito
Ombu_Settings.cfg hay que emprolijarlo al publico y agregarle mas precios o separarlos como genco decía en db
Alerta de expiración de buffs podría agregar contadores y cambiar la forma en la que aparece


