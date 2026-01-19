# Cornerfinder

Cornerfinder es una aplicación desarrollada en grupo como proyecto del ciclo de **Desarrollo de Aplicaciones Multiplataforma (DAM)**. Permite descubrir lugares secretos de A Coruña y obtener rutas personalizadas según los gustos del usuario para vivir una experiencia turística única. Este repositorio recopila y organiza todo el código del proyecto realizado de forma colaborativa.

<p align="left">
  <img src="https://img.shields.io/badge/Frontend-Android-brightgreen">
  <img src="https://img.shields.io/badge/Language-Java-orange">
  <img src="https://img.shields.io/badge/Build-Gradle-02303A">
</p>


## Índice

- [Cornerfinder](#cornerfinder)
  - [Índice](#índice)
  - [Apuntes y requisitos previos](#apuntes-y-requisitos-previos)
  - [Características](#características)
  - [Estructura del proyecto](#estructura-del-proyecto)
  - [Detalles técnicos](#detalles-técnicos)
  - [Guía de uso del proyecto](#guía-de-uso-del-proyecto)
    - [Frontend (Android)](#frontend-android)
    - [2.1 Abrir el proyecto en Android Studio:](#21-abrir-el-proyecto-en-android-studio)
    - [2.2 Configuración del Android SDK:](#22-configuración-del-android-sdk)
    - [2.3 Creación y ejecución de un emulador:](#23-creación-y-ejecución-de-un-emulador)
  - [4. Ejecución de la aplicación:](#4-ejecución-de-la-aplicación)


## Apuntes y requisitos previos

* El proyecto está pensado para ejecutarse en **Android Studio**.
* Para ejecutar el proyecto, se requiere de tener instaladas las siguientes herramientas:
    * **Android Studio** junto al **JDK 17**; que suele venir incluído.
    * **Git**


## Características

* Descubrimiento de lugares poco conocidos y “secretos” de A Coruña, enfocados en una experiencia turística alternativa.
* Recomendaciones personalizadas basadas en los gustos e intereses del usuario.
* Generación de rutas personalizadas hacia lugares exclusivos y menos turísticos.
* Backend basado en una API REST desarrollada con Django.
* Frontend implementado como aplicación Android nativa.


## Estructura del proyecto

```
cornerfinder/
├── code/
│   └── frontend/                 # Aplicación Android
│       ├── app/                  # Código fuente de la app
│       ├── gradle/               # Configuración de Gradle
│       └── recursos/             
├── doc/
├── logo/
└── README.md
```

La estructura del proyecto está organizada de forma modular.
El directorio **code** concentra el núcleo de la aplicación, y los directorios **doc** y **logo** se destinan a la documentación y al logo del proyecto respectivamente.


## Detalles técnicos

**Lenguajes:** Java y XML.

**Tecnologías y herramientas:** Android SDK y Gradle.

**Entorno:** Desarrollo local con emulador Android y gestión independiente de dependencias.


## Guía de uso del proyecto

### Frontend (Android)

### 2.1 Abrir el proyecto en Android Studio:

  1. Abrir **Android Studio**
  2. Seleccionar **Open**
  3. Abrir la carpeta: cornerfinder/code/frontend
  4. Esperar a que **Gradle sincronice** el proyecto


### 2.2 Configuración del Android SDK:

  En Android Studio:

  * **File → Settings → Android SDK**
  * Instalar:
    * Android SDK Platform (API 33 o superior)
    * Android SDK Build-Tools
    * Android Emulator


### 2.3 Creación y ejecución de un emulador:

  1. **Tools → Device Manager**
  2. Crear un dispositivo virtual (Pixel recomendado)
  3. Seleccionar Android API 33+
  4. Iniciar el emulador

## 4. Ejecución de la aplicación:

1. Comprobar que el server está siendo ejecutado (`python manage.py runserver`)
2. Tener el emulador de Android Studio iniciado.
3. Pulsar **Run ▶️** en Android Studio.
