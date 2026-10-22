# HoroCMS — Guía de instalación

*Beta 0.2.5*

Cómo instalar HoroCMS en un Mac o un PC con Windows y la aplicación complementaria en un teléfono, configurarlo, actualizarlo, trasladarlo a otro ordenador y desinstalarlo.

## Requisitos

- macOS 13 Ventura o posterior (Apple silicon o Intel), o Windows 10 u 11 (64 bits).
- Aplicación complementaria (opcional): Android 8 o posterior (64 bits), en la misma red Wi-Fi que el ordenador. La aplicación para iPhone (iOS 15 o posterior) aún no se ofrece al público.
- Unos 100 MB de disco para la aplicación, más espacio para sus fotos y documentos.
- No se necesita conexión a Internet. HoroCMS solo se conecta para buscar actualizaciones (www.leger.ca y GitHub, se puede desactivar), los tipos de cambio oficiales (Banco de Canadá, si los activa) y el asistente en línea (Anthropic, si lo activa).

## Obtener el instalador

HoroCMS es gratuito. Descárguelo desde la página pública de descargas:

https://github.com/ITriskMgr/HoroCMS-updates/releases/latest

En Assets, elija el archivo de su sistema: HoroCMS-Mac.dmg para un Mac (Apple silicon o Intel), HoroCMS-Windows-Setup.exe para Windows (o el .msi) y HoroCMS-Android.apk para un teléfono Android. No hace falta ninguna cuenta. La misma página ofrece estas guías en PDF.

## Instalar en un Mac

1. Descargue HoroCMS-Mac.dmg desde la página de descargas (vea Obtener el instalador) y ábralo.
2. Arrastre HoroCMS a Aplicaciones y ábralo desde Aplicaciones.
3. La beta aún no está firmada por Apple, así que macOS la bloquea la primera vez. En macOS 15 Sequoia o posterior: elija Aceptar, abra Ajustes del Sistema › Privacidad y seguridad, baje hasta «Se ha bloqueado HoroCMS», elija Abrir igualmente, confirme con su contraseña y luego Abrir. En macOS 13 o 14: haga clic derecho en HoroCMS en Aplicaciones, elija Abrir y luego Abrir de nuevo.

Si macOS dice que HoroCMS está dañado, abra Terminal y ejecute xattr -dr com.apple.quarantine /Applications/HoroCMS.app; luego ábralo de nuevo. macOS lo pregunta solo una vez.

Para actualizar, instale la nueva versión del mismo modo; su bóveda y sus ajustes se conservan. HoroCMS funciona en macOS 13 Ventura o posterior (Apple silicon e Intel).

## Instalar en Windows

1. Descargue HoroCMS-Windows-Setup.exe desde la página de descargas (vea Obtener el instalador) y ejecútelo. El .msi hace lo mismo para equipos administrados.
2. Si Windows SmartScreen indica que protegió su PC, elija Más información y luego Ejecutar de todas formas. La beta aún no está firmada, así que Windows avisa una vez.
3. Siga el instalador; HoroCMS aparece en el menú Inicio.

HoroCMS necesita Windows 10 u 11 con Microsoft Edge WebView2 (ya presente en las versiones actuales; el instalador lo añade si hace falta). La bóveda se guarda en los datos locales de la aplicación, que OneDrive no sincroniza.

## Crear su bóveda

HoroCMS guarda su colección en una bóveda cifrada en este ordenador. No se envía nada a ningún sitio.

1. Elija el idioma y el formato de números y fechas.
2. Elija una frase de contraseña de al menos 12 caracteres. Cuatro o cinco palabras poco comunes son fáciles de recordar y difíciles de adivinar.
3. Imprima o copie su clave de recuperación y vuelva a escribir su tercer grupo para confirmar que la tiene.

Guarde la clave de recuperación lejos del ordenador: con la documentación de sus relojes, en una caja fuerte o con su notario. Es la única forma de abrir la bóveda si olvida la frase.

## Instalar la aplicación complementaria en Android

1. En el teléfono, abra la página de descargas en el navegador (vea Obtener el instalador) y descargue HoroCMS-Android.apk. O descárguelo en el ordenador y cópielo al teléfono (cable, Google Drive o correo a usted mismo).
2. Abra el .apk descargado desde la notificación o la aplicación Archivos.
3. Android pide una vez permitir instalar aplicaciones de ese origen: permítalo y elija Instalar. Puede quitar ese permiso después.
4. Abra HoroCMS en el teléfono, elija una frase de contraseña para el teléfono y emparéjelo (vea Su colección en su teléfono).

Necesita Android 8 o posterior en un teléfono de 64 bits. Si la nueva versión no se instala sobre la anterior (beta firmada con otra clave), desinstale primero la anterior y vuelva a emparejar; no se pierde nada, la colección vuelve desde su ordenador.

## Instalar la aplicación complementaria en iPhone

La aplicación complementaria para iPhone aún no se ofrece al público: llegará mediante TestFlight de Apple. Use Soporte en HoroCMS para pedir que le avisen cuando esté lista.

Apple solo admite una aplicación en un iPhone si está firmada por una cuenta de desarrollador de Apple. Hasta entonces, los probadores la instalan de una de dos maneras:

- TestFlight (recomendado): con el Apple Developer Program (99 US$ al año). El autor compila la aplicación con su Team ID y la envía a TestFlight; usted instala la aplicación gratuita TestFlight desde el App Store, acepta la invitación e instala HoroCMS. Las actualizaciones llegan del mismo modo.
- Xcode, sin cuenta de pago: en un Mac con Xcode y un ID de Apple gratuito, la aplicación se instala por cable. Deja de abrirse a los 7 días y hay que instalarla de nuevo.

1. Una vez instalada, abra HoroCMS en el iPhone y permita la cámara (para leer el código QR de emparejamiento) y la red local (para llegar a su ordenador) cuando se pidan.
2. Elija una frase de contraseña para el teléfono y emparéjelo (vea Su colección en su teléfono).

Necesita iOS 15 o posterior. Los pasos técnicos para el autor están en docs/MOBILE.md.

## Su colección en su teléfono

La aplicación complementaria de HoroCMS para iPhone y Android muestra su colección con sus fotos, le permite ponerse y quitarse un reloj y lleva su lista de deseos. Lo que cambie en el teléfono vuelve a su ordenador.

En el ordenador, abra Ajustes › Aplicación complementaria para el teléfono, elija Activar la aplicación complementaria y luego Emparejar un teléfono (se pide su frase de contraseña). En el teléfono, elija una frase de contraseña para el teléfono y luego Escanear el código, o escriba la dirección y el código que muestra el ordenador. Ambos deben estar en la misma red Wi-Fi.

El teléfono guarda su propia copia cifrada de la colección y se bloquea al salir de la aplicación. Solo habla con su ordenador, en su red doméstica, y solo mientras HoroCMS está desbloqueado allí; nada pasa por Internet. Si sus ordenadores se sincronizan mediante una carpeta en la nube, el teléfono también recibe lo que envían los demás ordenadores.

La primera vez, macOS o Windows pueden preguntar si HoroCMS puede aceptar conexiones entrantes: permítalo solo en redes privadas. Desactive la aplicación complementaria en el mismo lugar cuando no la necesite. Si olvida la frase de contraseña del teléfono, borre sus datos desde su pantalla de desbloqueo y vuelva a emparejarlo.

## Actualizar HoroCMS

Al iniciarse, HoroCMS pregunta a www.leger.ca y a GitHub si existe una versión más reciente (solo se envía el número de versión de la aplicación). Si la hay, un aviso se la ofrece; Ajustes › Actualizaciones › Buscar ahora hace lo mismo en cualquier momento. Desactive allí la búsqueda al iniciar para mantener HoroCMS completamente sin conexión.

1. Haga una copia de seguridad (Ajustes › Copias de seguridad). HoroCMS se lo recuerda si la última tiene más de un día.
2. Haga clic en Instalar y reiniciar. HoroCMS se bloquea, descarga la actualización, comprueba que está firmada por su autor (rechaza cualquier otra), la instala y se reinicia.
3. Desbloquee como de costumbre. Su colección se conserva automáticamente: HoroCMS guarda una copia, la actualiza, comprueba cada ficha y vuelve a poner la copia si algo falla.

Su bóveda, sus preferencias y sus copias automáticas se quedan donde están; una actualización nunca las borra. Las fotos y documentos no se tocan.

También puede instalar una nueva versión a mano, como la primera vez (vea Instalar en Mac o en Windows): la misma actualización segura se hace al desbloquear.

Si HoroCMS indica que no pudo actualizar la bóveda, no se ha cambiado nada: vuelva a instalar la versión anterior para seguir trabajando y contacte con el autor. Una bóveda usada por una versión más reciente no puede abrirse con una más antigua; actualice la aplicación.

## Restaurar una copia o cambiar de ordenador

En un ordenador nuevo, elija Restaurar una copia… en la primera pantalla; en este, use la pantalla de desbloqueo o Ajustes.

1. Elija el archivo de copia (.horobak).
2. Escriba su frase de contraseña.
3. Elija la frase de la bóveda restaurada.

Todo se comprueba antes de tocar la bóveda actual, que se conserva aparte. Recibirá una nueva clave de recuperación para imprimir.

## Copias de seguridad

HoroCMS hace automáticamente una copia cifrada tras desbloquear, como mucho una vez al día, en la carpeta de datos de HoroCMS (o una carpeta de su elección; Ajustes › Copias de seguridad › Mostrar en Finder o el Explorador la abre). Conserva las 10 más recientes. Cada copia automática se abre con la frase con la que desbloqueó ese día.

Para hacer una usted mismo, vaya a Ajustes › Copias de seguridad, elija una frase para ella y Guardar una copia…, y luego un lugar como una memoria USB. Guarde al menos una copia lejos del ordenador.

## Si algo sale mal

HoroCMS comprueba todo lo que lee, así que un daño se detecta en lugar de mostrarse como un dato erróneo. Pueden ocurrir dos tipos de problema tras un fallo de disco o un cierre inesperado.

La colección no se abre, aunque la frase de contraseña sea correcta. HoroCMS ofrece entonces dos salidas:

- Volver a una copia automática: HoroCMS guarda una antes de cada actualización. Se pierden los cambios hechos después; las fotos y documentos no se ven afectados. El archivo dañado se guarda aparte.
- Restaurar una copia de seguridad: elija la más reciente (vea Restaurar una copia de seguridad).

Faltan fotos o documentos, o están dañados. Ajustes › Estado de la bóveda › Comprobar la bóveda los detecta. Elija una copia hecha cuando estaban bien y escriba su frase: HoroCMS recupera solo esos archivos, tras comprobar cada uno. Los archivos que no estén en ninguna copia pueden quitarse de la ficha; el reloj en sí no se ve afectado.

Guarde copias en una memoria USB u otro disco, no solo en este ordenador: son las que permiten recuperarse de cualquier problema.

## Dónde están sus datos

- Mac: ~/Library/Application Support/ca.leger.horocms/vault (cifrado).
- Windows: %LOCALAPPDATA%\ca.leger.horocms\vault (cifrado; OneDrive no lo sincroniza).
- Copias automáticas: la carpeta Backups junto a la bóveda (antes de la versión 0.2.1: Documentos/HoroCMS Backups), salvo que eligiera otra carpeta.
- Preferencias (idioma, tema, moneda): un pequeño archivo en la carpeta de ajustes del sistema; no contiene nada sobre su colección.

## Desinstalar HoroCMS

Haga primero una copia (Ajustes › Copias de seguridad). En Mac, arrastre HoroCMS de Aplicaciones a la Papelera; en Windows, use Configuración › Aplicaciones › HoroCMS › Desinstalar. La bóveda cifrada se conserva para que una reinstalación encuentre su colección; borre la carpeta indicada arriba si quiere eliminarla.

---

© 2026 Marc-André Léger. Todos los derechos reservados. Creado con Claude (Anthropic).
