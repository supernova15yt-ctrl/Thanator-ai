THANATOR AI - VERSION 1.0 (PROTOTIPO PWA)

Qué incluye:
- Generador local de 10 borradores con enfoques diferentes.
- Duración seleccionable (30, 40, 60 y 90 segundos como objetivo aproximado).
- Títulos y hashtags sugeridos.
- Biblioteca local con guardar, copiar, eliminar y exportar.
- Vista previa de fotografía.
- Diseño adaptable a móvil y caché offline tras la primera carga.

IMPORTANTE:
Esta versión NO usa un modelo de IA. La generación se basa en plantillas y en las características que escriba el usuario. No analiza el contenido de la foto; solo muestra una vista previa. Es una base funcional gratuita, no una IA generativa completa.

INSTALACIÓN EN ANDROID:
1. Publica el contenido de esta carpeta en un hosting HTTPS gratuito que permita archivos estáticos (por ejemplo, GitHub Pages).
2. Abre la dirección HTTPS desde Chrome en Android.
3. Menú de Chrome > "Instalar aplicación" o "Añadir a pantalla de inicio".
4. Abre Thanator AI desde el icono.

NOTA SOBRE APK:
Este paquete es una PWA instalable desde Chrome; todavía no es un APK independiente. Para generar un APK firmado se requiere empaquetar el proyecto y compilarlo con herramientas Android (por ejemplo, Capacitor + Android Studio/SDK). No se ha generado ni firmado un APK en este paquete.

PRIVACIDAD:
Los guiones guardados se almacenan en localStorage del navegador/dispositivo. No hay cuenta ni servidor. Si borras los datos del navegador, podrías perder la biblioteca. Usa Exportar biblioteca para hacer una copia JSON.

ARCHIVOS:
index.html       Interfaz
app.js           Funciones
manifest.webmanifest  Datos de instalación PWA
sw.js            Caché offline
icon.svg         Icono
