# Mi App Web

Aplicación web estática optimizada y desplegada con Apache en Windows, desarrollada en Visual Studio Code.

## 📋 Descripción

Proyecto del Reto 2 del módulo **Despliegue de Aplicaciones Web y Móviles**. Se empaquetó, versionó y desplegó una aplicación web estática usando Apache como servidor local.

## 🚀 Proceso realizado

### 1. Preparación de la aplicación web
- Estructura modular: `css/`, `js/`, `img/`.
- Imágenes optimizadas con Image Optimizer (calidad 80%).
- CSS y JS minificados con extensión Minify de VS Code.

### 2. Empaquetado
- Generado `mi-app.zip` con la estructura final lista para subir al servidor.

### 3. Versionado
- Repositorio Git inicializado en VS Code.
- Subido a GitHub con commits descriptivos.
- Tag de versión `v1.0.0`.

### 4. Despliegue con Apache
- XAMPP instalado en Windows (incluye Apache 2.4).
- Archivos de la aplicación copiados a `C:\xampp\htdocs\mi-app\`.
- Alias `/mi-app` configurado en `C:\xampp\apache\conf\httpd.conf`.

## 🛠️ Tecnologías utilizadas

- HTML5, CSS3, JavaScript
- Visual Studio Code
- Apache 2.4 (Windows)
- Git + GitHub

## 🌐 Acceso local

Una vez configurado Apache: `http://localhost/mi-app`

## 📁 Estructura del proyecto

mi-app/
├── index.html
├── README.md
├── .gitignore
├── css/
│ ├── styles.css
│ └── styles.min.css
├── js/
│ ├── app.js
│ └── app.min.js
└── img/
└── logo.png

## 👤 Autor

**Jesús Erubey Gómez Hernández**
Universidad Virtual del Estado de Guanajuato (UVEG)
Materia: Despliegue de Aplicaciones Web y Móviles
Reto 2