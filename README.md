<a name="readme-top"></a>

<div align="center">

<img src="logo.png" alt="logo" width="140" height="auto" style="border-radius:50%" />
<br/>
<h3><b>WEBPACK AZURE PROJECT</b></h3>

</div>

# ✅ TABLE OF CONTENTS
- [✅ TABLE OF CONTENTS](#-table-of-contents)
- [📖 \[WEBPACK AZURE PROJECT\]](#-webpack-azure-project)
  - [⚒️ Build With ](#️-build-with-)
    - [Tech Stack ](#tech-stack-)
    - [Key Features ](#key-features-)
  - [💻 Getting Started ](#-getting-started-)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
    - [Project Commands](#project-commands)

# 📖 [WEBPACK AZURE PROJECT]<a name="about-project"></a>

*[Webpack Azure Project]* This project is part of the SENA Software Development Analysis curriculum, focused on deploying a web application using Webpack and Azure.

## ⚒️ Build With <a name="built-with"></a>

<p>
This project was built using:
HTML, CSS, JavaScript, Webpack, Linters, GitHub, and Azure.
</p>

### Tech Stack <a name="tech-stack"></a>

<li> HTML </li>
<li> CSS </li>
<li> JavaScript </li>
<li> Webpack </li>
<li> Linters (ESLint, Stylelint, Webhint) </li>
<li> GitHub </li>
<li> Azure </li>

<details>
<summary> Client </summary>
    <ul>
    <li><a href="https://developer.mozilla.org/es/docs/Web/HTML">HTML</a></li>
    <li><a href="https://developer.mozilla.org/es/docs/Web/CSS">CSS</a></li>
    <li><a href="https://developer.mozilla.org/es/docs/Web/JavaScript">JavaScript</a></li>
    </ul>
</details>

<details>
<summary>Tools</summary>
<ul>
<li><a href="https://webpack.js.org/">Webpack</a></li>
<li><a href="https://eslint.org/">ESLint</a></li>
<li><a href="https://stylelint.io/">Stylelint</a></li>
<li><a href="https://webhint.io/">Webhint</a></li>
</ul>
</details>

### Key Features <a name="key-features"></a>

- **Linting**: Automated code quality checks using ESLint, Stylelint, and Webhint.
- **Webpack**: Bundling and optimization of assets.
- **Azure Deployment**: Continuous deployment to Azure using GitHub Actions.

<p align="right"><a href="#readme-top">Back to top</a></p>

## 💻 Getting Started <a name="getting-started"></a>

To get a local copy up and running, follow these steps:

### Prerequisites

To run this project, you need the following tools:

- [VS Code](https://code.visualstudio.com/)
- [Git and GitHub](https://github.com/)
- [Node.js](https://nodejs.org/)
- [Azure CLI](https://learn.microsoft.com/en-us/cli/azure/)

### Setup

Clone this repository to your desired folder:

```sh
cd FormularioLinters
git clone https://github.com/JhonDiaz15/FormularioLinters.git
```

Install dependencies:
```sh
npm install
```

Start the development server:
```sh
npm start
```

### Project Commands

Below are the commands used in the project, from initial setup to deployment on Azure:

***Project Initialization***
```sh
npm init -y
```

***Linters Installation***

Hint: 
```sh
npm install --save-dev hint@7.x
```
Stylelint:
```sh
npm install --save-dev stylelint@13.x stylelint-scss@3.x stylelint-config-standard@21.x stylelint-csstree-validator@1.x
```
ESLint:
```sh
npm install --save-dev eslint@7.x eslint-config-airbnb-base@14.x eslint-plugin-import@2.x babel-eslint@10.x
```

***Running Linters***

Hint: 
```sh
npx hint .
```
Stylelint: 
```sh
npx stylelint "**/*.css"
```
ESLint:
```sh
npx eslint .
```

***Automatic Error Fixing***

Stylelint:
```sh
npx stylelint "**/*.css" --fix
```
ESLint: 
```sh
npx eslint . --fix
```

***Webpack Installation***
```sh
npm install webpack webpack-cli --save-dev
```

***Webpack Loaders and Plugins Configuration***

CSS Loader: 
```sh
npm install --save-dev style-loader css-loader
```
HTML Loader: 
```sh
npm install --save-dev html-loader
```
HTML Webpack Plugin: 
```sh
npm install --save-dev html-webpack-plugin
```
Webpack Dev Server: 
```sh
npm install --save-dev webpack-dev-server
```

***Babel Configuration***
```sh
npm install --save-dev babel-loader @babel/core @babel/preset-env
```

***Project Bundling***

Development Mode: 
```sh
npm run build-dev
```
Production Mode: 
```sh
npm run build-prod
```

***Starting the Development Server***
```sh
npm start
```

***Express Installation***
```sh
npm install express
```

***Production Server Configuration***
```sh
node server.js
```

***Deployment to Azure***
GitHub Actions Configuration: See azure-deploy.yml file.

***Pushing Changes to GitHub:***
```sh
git add .
git commit -m "Commit message"
git push origin main
```

<p align="right"><a href="#readme-top">Back to top</a></p>

## 👥 Authors <a name="authors"></a>

🧑🏻‍💻 Jhon Diaz

GitHub: [@JhonDiaz15](https://github.com/JhonDiaz15)

<p align="right"><a href="#readme-top">Back to top</a></p>
