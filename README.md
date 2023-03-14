<!-- Logo -->
<p align="center">
  <h1>iWebTMT<span style="color:#f2780c"></h1>
</p>

<!-- Badges -->
<p align="center">
  <a href="https://developer.mozilla.org/en-US/docs/Glossary/HTML5">
    <img alt="HTML5" src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  </a>
  
  <a href="https://developer.mozilla.org/en-US/docs/Glossary/CSS3">
    <img alt="CSS3" src="https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white" />
  </a>
  
  <a href="https://javascript.org/">
    <img alt="Javascript" src="https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E" />
  </a>
  
  <a href="https://reactjs.org/">
    <img alt="React" src="https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" />
  </a>
  
  <a href="https://nodejs.org/">
    <img alt="NodeJS" src="https://img.shields.io/badge/node.js-6DA55F?style=for-the-badge&logo=node.js&logoColor=white" />
  </a>
  
  <a href="https://firebase.google.com/?hl=pt">
    <img alt="Firebase" src="https://img.shields.io/badge/Firebase-F29D0C?style=for-the-badge&logo=firebase&logoColor=white" />
  </a>
  
   <a href="https://github.com/">
    <img alt="Github" src="https://img.shields.io/badge/GitHub-100000?style=for-the-badge&logo=github&logoColor=white" />
  </a>
  
</p>

<h2>Summary</h2>

- [🔖 About](#about)
- [💻 Demo](#demo)
- [🚀 Localhost](#localhost)

<a id="about"></a>

## 🔖 About

**iWebTMT** é uma aplicação que busca apresentar as ferramentas mais utilizadas atualmente no mercado de trabalho na área de desenvolvimento web.

<a id="demo"></a>

## 💻 Demo

A Aplicação está hospedada em [Firebase Hosting]() e pode ser encontrada aqui: [iWebTMT]().

<a id="localhost"></a>

## 🚀 Localhost

- Para rodar localmente, primeiramente será necessário criar um projeto no [firebase](https://console.firebase.google.com/u/0/?hl=pt), clique em *Adicionar projeto* e siga as etapas.
- Após criar o projeto, utilizando a barra lateral, vá em *configurações* (ícone de engrenagem), configurações do projeto e criar um app da web.
- Criado o app, na barra lateral clique em *Criação* e vá em *Firestore Database*, e siga o fluxo de trabalho para a criação do banco de dados.
- Clone esse repositório *git clone https://github.com/AmandaE19/iWebTMT.git*
- Em seu editor de texto (Ex: VSCode) baixe os pacotes necessário, abra um terminal na raiz da pasta server e rode o comando *npm i* e faça o mesmo na raiz da pasta client
- Na raiz da pasta server crie um arquivo chamado "credentials.json" e insira as informações do seu projeto firestore (Vá em configurações do projeto no firestore, na opção contas de serviço, clique no botaõ Gerar nova chave privada)
  {
    "type": "service_account",
    "project_id": "PROJECT ID",
    "private_key_id": "PRIVATE KEY ID",
    "private_key": "PRIVATE KEY",
    "client_email": "CLIENT EMAIL",
    "client_id": "CLIENT ID",
    "auth_uri": "AUTH URI",
    "token_uri": "TOKEN URI",
    "auth_provider_x509_cert_url": "AUTH PROVIDER",
    "client_x509_cert_url": "CLIENT"
  }
- Após baixar, na raiz da pasta client use o comando *npm start* para rodar o frontend localmente e na raiz da pasta server execute o comando *npm start*. Pronto!
