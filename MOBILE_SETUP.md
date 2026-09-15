# Holguín Taxi — preparación desde celular

## 1. Crear la plataforma Android

Este repositorio contiene el código Flutter, pero todavía no incluye la carpeta `android/`.
En un entorno Flutter en la nube, desde la raíz del proyecto, ejecutar:

```bash
flutter create --platforms=android .
flutter pub get
flutter analyze
```

## 2. Primera compilación de prueba

```bash
flutter build apk --debug
```

El APK quedará en:

`build/app/outputs/flutter-apk/app-debug.apk`

## 3. Importante

Antes de producción hay que configurar Supabase, permisos de ubicación, firma Android y revisar las políticas de mapas/OSM. Esta versión es una candidata para pruebas, no se debe considerar todavía una versión de producción.
