# 📦 Projeto Gulp + SPA

Este repositório contém um conjunto de experimentos e práticas com **Gulp**, automatizando tarefas de build e finalizando em um **projeto SPA (Single Page Application)** com navegação via **AJAX**.

---

## 🚀 Funcionalidades

Durante o desenvolvimento, foram implementadas várias etapas de automação:

- **Concatenação de arquivos** (JS e CSS).  
- **Minificação**: códigos reduzidos para apenas **uma linha**.  
- **Transpilação com Babel**: conversão de código ES6+ para ES5.  
- **Compilação de TypeScript para JavaScript**.  
- **Compilação de SASS para CSS**.  
- **Cópia de arquivos e assets** (HTML, imagens, fontes).  
- **Serviço local com LiveReload** para facilitar o desenvolvimento.  
- **Monitoramento de arquivos**: alterações em tempo real recompilam o projeto.  
- **SPA com navegação via AJAX**, sem recarregar a página.

---

## 🛠️ Tecnologias utilizadas

- [Node.js](https://nodejs.org/)  
- [Gulp](https://gulpjs.com/)  
- [Babel](https://babeljs.io/)  
- [TypeScript](https://www.typescriptlang.org/)  
- [SASS](https://sass-lang.com/)  
- [Uglify](https://www.npmjs.com/package/gulp-uglify)  
- [UglifyCSS](https://www.npmjs.com/package/gulp-uglifycss)  
- [Concat](https://www.npmjs.com/package/gulp-concat)  
- [HTMLMin](https://www.npmjs.com/package/gulp-htmlmin)  
- [Font Awesome](https://fontawesome.com/)  
- [gulp-webserver](https://www.npmjs.com/package/gulp-webserver)

---

## 🖥️ SPA com Navegação AJAX
O projeto final implementa uma SPA (Single Page Application) simples, com navegação dinâmica via hash e carregamento de conteúdo com Fetch API.
- O atributo personalizado wm-link define o destino da navegação. 
- O conteúdo das páginas é carregado dinamicamente sem recarregar o site.  
- O link ativo recebe a classe selecionado.

---

## ▶️ Como utilizar o projeto
1. Clonar o repositório  
   ```bash
   git clone https://github.com/DaviAfonso88/Gulp.git
2. Instalar dependências
   ```bash
   npm install
4. Rodar o build
   ```bash
   gulp
   
---

## 👨‍💻 Desenvolvido por

<table>
  <tr>
    <td align="center">
      <a href="#">
         <img src="https://avatars.githubusercontent.com/u/89953265?v=4" width="100px;" alt="Foto de Davi Afonso no GitHub"/><br>
        <sub>
          <b>Davi Afonso</b>
        </sub>
      </a>
    </td>
</table>
