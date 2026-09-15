DEXTOR · APLICACIÓN ANDROID

URL conectada:
https://dextorarg.vercel.app/

Paquete Android:
com.dextor.app

Versión:
1.0

Android mínimo:
Android 7.0 (API 24)

Esta app es un contenedor Android WebView seguro de tu web DEXTOR.
Por eso, cuando actualizás la web en Vercel, la app muestra los cambios
sin tener que volver a crear el APK.

FUNCIONES INCLUIDAS
- Inicio de sesión y sesión persistente por cookies.
- JavaScript y almacenamiento web.
- Selector de archivos.
- Navegación Atrás de Android.
- Enlaces externos tipo WhatsApp/teléfono/correo.
- HTTPS obligatorio.
- Los errores SSL se bloquean.
- Icono y pantalla de inicio DEXTOR.

FORMA MÁS FÁCIL DE CREAR EL APK
1. Subí esta carpeta completa a un repositorio de GitHub.
2. Entrá en la pestaña Actions.
3. Abrí "Crear APK DEXTOR".
4. Tocá "Run workflow".
5. Cuando termine, descargá el artifact "DEXTOR-Android".
   Adentro va a estar DEXTOR.apk listo para instalar.

También podés abrir esta carpeta con Android Studio y usar:
Build > Build APK(s)

IMPORTANTE:
El APK de GitHub Actions será una compilación DEBUG firmada automáticamente
por Android. Sirve para instalar y probar directamente en teléfonos Android.
Para publicar en Google Play conviene generar una versión RELEASE firmada
con tu propia clave privada.
