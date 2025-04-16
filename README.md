# 🎬 Movies App

Aplicación iOS desarrollada en Swift que implementa la arquitectura **MVP (Model-View-Presenter)** junto con el patrón **Coordinator**, demostrando buenas prácticas en diseño de software y navegación desacoplada.

## 🧠 Características principales

- Arquitectura basada en **MVP + Coordinator** para una separación clara de responsabilidades.
- Uso de **CocoaPods** para la gestión de dependencias.
- Aplicación modular y escalable, preparada para futuras integraciones.
- Código limpio y organizado, siguiendo las convenciones de Swift.

## 📸 Capturas de pantalla

*Aquí puedes incluir imágenes de la interfaz de la aplicación para mostrar su diseño y funcionalidades.*

## 🛠️ Tecnologías utilizadas

- **Swift**
- **Xcode**
- **CocoaPods**
- **MVP**
- **Coordinator Pattern**

## 🚀 Cómo ejecutar el proyecto

1. Clona este repositorio:
   ```bash
   git clone https://github.com/Kordragx/Movies.git
   cd Movies
   pod install
   open Movies.xcworkspace

## 📁 Estructura del proyecto

```plaintext
Movies/
├── AppDelegate.swift
├── Coordinators/
│   └── AppCoordinator.swift
├── Models/
│   └── Movie.swift
├── Presenters/
│   └── MoviePresenter.swift
├── Views/
│   └── MovieViewController.swift
├── Resources/
│   └── Assets.xcassets
├── Supporting Files/
│   └── Info.plist

