# RN76 - Inspección Zona Oeste — APK Android

Este proyecto convierte la aplicación HTML de RN76 en una aplicación Android instalable, usando WebView y el logo de **Inspección Zona Oeste** como icono.

## Opción recomendada: generar el APK automáticamente con GitHub

No hace falta instalar Android Studio en la PC.

1. Entrar a https://github.com/ e iniciar sesión.
2. Crear un repositorio nuevo, por ejemplo `RN76-Inspeccion-Zona-Oeste`.
3. Subir **el contenido de esta carpeta** al repositorio (debe quedar visible `app/`, `build.gradle`, `settings.gradle` y `.github/`).
4. En GitHub abrir la pestaña **Actions**.
5. Seleccionar **Generar APK RN76 - Inspección Zona Oeste**.
6. Pulsar **Run workflow**.
7. Esperar a que finalice el proceso.
8. Abrir la ejecución terminada y bajar el artefacto **RN76-Inspeccion-Zona-Oeste-APK**.
9. Dentro del ZIP estará `app-debug.apk`.
10. Copiar el APK al celular Android, abrirlo y aceptar la instalación.

### Requisitos del celular

- Android 6.0 o superior.
- Para instalar el APK descargado manualmente, Android puede solicitar autorización para instalar aplicaciones desde esa fuente.

## Compilación con Android Studio

Abrir esta carpeta como proyecto Android y ejecutar:

**Build → Build APK(s)**

El resultado será:

`app/build/outputs/apk/debug/app-debug.apk`

## Datos del proyecto

- Nombre: RN76 - Inspección Zona Oeste
- Package: `com.apv.rn76zonaoeste`
- Min SDK: 23
- Target SDK: 35
- Icono: Inspección Zona Oeste
- Aplicación HTML: `app/src/main/assets/index.html`
