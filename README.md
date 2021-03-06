# brotes
Documentando la app de Brotes.

La app "Orar con Brotes de Olivo" te permite escuchar 3 canciones del grupo Brotes de Olivo (intro, medio, final), dejando una pausa entre ellas. La combinación de canciones varía cada día entre una selección de canciones, que debe estar en la memoria interna del teléfono.
La pausa puede variar entre 30 y 180 segundos, según elija el usuario.
Las canciones deben estar en la memoria interna del teléfono, en una carpeta llamada "App_BrotesDeOlivo", situada en la raíz de la memoria interna. 
La selección de música puede descargarse desde este repositorio, o bien desde Dropbox en la dirección https://www.dropbox.com/s/rqba0wm3rtu68i0/App_BrotesDeOlivo.zip?dl=1.

Esta versión (desfasada) de la app está elaborada mediante la herramienta "App Inventor 2" del MIT, accesible en la dirección: http://ai2.appinventor.mit.edu. Probablemente no volverá a actualizarse en AI2.

Si deseas una versión optimizada, visita la versión Javascript, en https://github.com/luisgentil/brotesJS.

# Instalación
Descarga la app (archivo .apk) en tu teléfono android. Al hacer click debe ofrecerte la opción de instalar, acepta.
Si no te permite instalar, activa la opción Ajustes > Seguridad > Orígenes desconocidos.
Descarga el archivo *AppBrotesDeOlivo.zip *. a tu teléfono. Si lo haces desde el propio teléfono, lo más probable es que esté descargado en una de las carpetas:
  - Downloads
  - My Documents/Downloads (más probable)
Necesitarás una aplicación que pueda acceder a las carpetas, descomprimir archivos y moverlos. Yo he usado *ES File Explorer*., es fácil de usar y muy eficaz. Disponible gratis en Google Play. 
Desde la carpeta donde esté situado el fichero descargado, selecciona el fichero y elige la opción Más > Descomprimir.
Cuando haya terminado, selecciona la carpeta creada y elige la opción Más > Mover A. En la pantalla que se abre, navega hasta *Internal Storage*., y elige esa ubicación para la carpeta.
En algunos teléfonos, podrás ver alguna de las siguientes expresiones para referirse a Internal Storage:
  - *storage > emulated > 0*.
  - */sdcard/*.

NO debes elegir otra ubicación parecida (como "storage/sdcard1" (o 2, 3,...) ), porque corresponden a la tarjeta SD física que puede tener tu teléfono; si grabas la música ahí no podrás usarla en la aplicación.

# Mejoras previstas
Entre las mejoras posibles se encuentran:
- versión de escritorio:  ya disponible en (provisional: luisgentil.neocities.org)
- reproducción on-line: ya disponible desde la versión Javascript https://github.com/luisgentil/brotesJS .
- almacenar las canciones en la tarjeta SD del móvil (por ahora sólo es posible escucharlas desde la memoria interna): ya disponible en la versión Javascript https://github.com/luisgentil/brotesJS .
- selección de temas de oración: pendiente

# Beta 2
Se añade un elemento extra para evitar que la aplicación entre en pausa, cortando la ejecución de las canciones.
