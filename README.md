# PAN para Android — proyecto de aplicación

Este proyecto empaqueta el juego PAN 0.7 (comercio y pedidos) dentro de una aplicación Android mediante WebView. El juego se incluye en `app/src/main/assets/index.html`, no requiere conexión a Internet y no solicita permisos de red. El progreso del juego se guarda localmente mediante el almacenamiento del navegador.

## Crear el APK con Android Studio

1. Instala Android Studio en un ordenador: https://developer.android.com/studio
2. Descomprime `PAN_Android_Proyecto.zip`.
3. En Android Studio, elige **Open** y selecciona la carpeta `PAN_Android` (la que contiene `settings.gradle`).
4. Acepta la instalación de los componentes Android SDK que Android Studio solicite y espera a que termine la sincronización de Gradle.
5. En el menú, elige **Build > Build Bundle(s) / APK(s) > Build APK(s)**.
6. Android Studio generará el APK. Normalmente quedará en `app/build/outputs/apk/debug/app-debug.apk`.
7. Pasa el APK al teléfono Android y ábrelo para instalarlo. Si Android lo solicita, autoriza temporalmente la instalación desde esa fuente.

## Datos técnicos

- Nombre: PAN
- Versión: 0.7.0
- Paquete: `com.pan.granja`
- Orientación: vertical
- Android mínimo: Android 6.0 (API 23)
- Juego integrado: HTML local; no necesita Internet
- Guardado: almacenamiento local de WebView

## Nota

Este entorno no dispone de Android SDK/Gradle instalados, así que aquí se prepara el proyecto Android listo para abrir y compilar, pero no se ha generado un APK ni se ha probado en un dispositivo físico. El archivo HTML original también se conserva por separado.
