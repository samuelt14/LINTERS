<a name="readme-top"></a>

<div align="center">

<h3><b>📦 FORMULARIO INTERACTIVO CON WEBPACK</b></h3>

</div>

# ✅ CONTENIDO
- [📖 Acerca del Proyecto](#about-project)
  - [⚒️ Tecnologías Utilizadas](#built-with)
    - [Stack Principal](#tech-stack)
    - [Funciones Clave](#key-features)
  - [🚀 Vista en Vivo](#live-demo)
- [💻 Primeros Pasos](#getting-started)
  - [Requisitos Previos](#prerequisites)
  - [Instalación](#install)
  - [🧠 Uso de JavaScript](#javascript-usage)
  - [☕ Uso de Java (Opcional)](#java-optional)
  - [🧪 Testing](#testing)
- [👥 Autoría](#authors)
- [🔮 Próximas Funciones](#future-features)
- [🤝 Cómo Contribuir](#contributing)
- [⭐ Apoya el Proyecto](#support)
- [🙌 Agradecimientos](#acknowledgements)
- [📃 Licencia](#license)

# 📖 Acerca del Proyecto <a name="about-project"></a>

**Formulario Interactivo con Webpack** es un proyecto simple pero funcional creado como parte de mi formación en el SENA. Este proyecto muestra cómo estructurar un formulario web utilizando herramientas modernas de desarrollo como Webpack, HTML, CSS y JavaScript.

---

## ⚒️ Tecnologías Utilizadas <a name="built-with"></a>

### Stack Principal <a name="tech-stack"></a>

- HTML5
- CSS3
- JavaScript ES6+
- Webpack

<details>
<summary>Recursos</summary>
<ul>
  <li><a href="https://developer.mozilla.org/es/docs/Web/HTML">HTML</a></li>
  <li><a href="https://developer.mozilla.org/es/docs/Web/CSS">CSS</a></li>
  <li><a href="https://webpack.js.org/">Webpack</a></li>
</ul>
</details>

### Funciones Clave <a name="key-features"></a>

- ✨ Formulario estilizado e interactivo  
- ⚙️ Configuración automatizada con Webpack  
- 📁 Organización modular del código  
- 🧼 Linters integrados (.stylelintrc, .hintrc)

<p align="right"><a href="#readme-top">Volver arriba</a></p>

---


## 💻 Primeros Pasos <a name="getting-started"></a>

### Requisitos Previos <a name="prerequisites"></a>

- Node.js y npm instalados  
- Un editor como Visual Studio Code  

### Instalación <a name="install"></a>

Clona el repositorio e instala las dependencias:

```bash
git clone https://github.com/samuelt14/LINTERS.git
cd Proyecto_formulario
npm install
Instala herramientas de desarrollo:
```
```bash
# Webpack
npm install --save-dev webpack webpack-cli webpack-dev-server
```
```bash
# Loaders para CSS y HTML
npm install --save-dev style-loader css-loader html-webpack-plugin
```
```bash
# Babel
npm install --save-dev @babel/core @babel/preset-env babel-loader
```
```bash
# Linters
npm install --save-dev stylelint stylelint-config-standard stylelint-config-recommended
npm install --save-dev hint
```
```bash
Uso de JavaScript <a name="javascript-usage"></a>
Scripts en el archivo package.json:

"scripts": {
  "start": "webpack serve --open",
  "build": "webpack --mode production",
  "hint": "hint .",
  "stylelint": "stylelint '**/*.css'",
  "test": "jest"}
  ```
Comandos disponibles:
```bash
npm run start       # Servidor de desarrollo
```
```bash
npm run build       # Compila el proyecto
```
```bash
npm run hint        # Revisión de errores HTML
```
```bash
npm run stylelint   # Revisión de estilos CSS
```

```bash
ESLint
#ayuda a encontrar errores y mantener buenas prácticas en el código JavaScrip
npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x
#se utiliza para ejecutar ESLint en todo tu proyecto,
```
```bash
Run npx eslint . 
```
```bash
Stylelint
#verifica y valida que el código CSS o SCSS siga buenas prácticas y convenciones.
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```
```bash
#Puedes añadir estos comandos como scripts personalizados en tu package.json para ejecutarlos fácilmente.
Run npx stylelint "**/*.{css,scss}" 
```
👥 Autoría <a name="authors"></a>
👩‍💻 Samuel Torres
Estudiantes de desarrollo de software – SENA
GitHub: @samuelt14