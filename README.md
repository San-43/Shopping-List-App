# Shopping List App

Aplicación móvil hecha en Flutter para gestionar una lista de compras con categorías, cantidades y sincronización en tiempo real mediante Firebase Realtime Database.

## ✨ Características

- Listado de productos con nombre, cantidad y categoría.
- Alta y baja de productos desde la interfaz.
- Sincronización con Firebase Realtime Database.
- Tema oscuro personalizado.

## 🧱 Tecnologías

- Flutter
- Dart
- Firebase Realtime Database

## ✅ Requisitos

- Flutter SDK instalado (https://docs.flutter.dev/get-started/install)
- Emulador Android/iOS o dispositivo físico

## 🚀 Ejecución local

1. Instala las dependencias:

   ```bash
   flutter pub get
   ```

2. Ejecuta la app:

   ```bash
   flutter run
   ```

## 🔧 Configuración de Firebase

La app utiliza una instancia de Firebase Realtime Database configurada en el código (`lib/widgets/grocery_list.dart`).
Si quieres usar tu propia base de datos:

1. Crea un proyecto en Firebase.
2. Habilita Realtime Database.
3. Sustituye el host en el `Uri.https(...)` por el de tu proyecto.

## 🗂 Estructura del proyecto

```
lib/
  data/          # Datos y constantes (categorías)
  models/        # Modelos de datos
  widgets/       # Widgets de UI
  main.dart      # Punto de entrada
```

## 📄 Licencia

Este proyecto se proporciona como ejemplo educativo. Puedes adaptarlo libremente.
