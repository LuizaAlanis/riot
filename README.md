# Riot

Insert e select de champions com o estilo do site do league of legends: wild rift

## 📌 Estrutura do projeto

<ul>
  <li>Na verdade, temos dois projetos:
    <ul>
      <li>Um projeto Client Side, com o React.js e que consome a API em Node.js.</li>
      <li>Um projeto Server Side, que manipula e resgata dados de um banco MySQL. Transformando em um json para que o Front-end em React.js possa consumir.</li>
    </ul>
  </li>
</ul>

## 🚀 Começando

<ul>
  <li>Faça o download do projeto pelo git</li>
  <li>Abra no seu editor de código preferido ou IDE</li>
  <li>Caso esteja no VSCode, você pode abrir dois terminais para rodar cada projeto, execute o "npm start" ou "yarn start".
    <ul>
      <li>Em um cmd você teria algo: \riot\client npm start</li>
      <li>E no outro: \riot\server npm start</li>
    </ul>
  </li>
  <li><i> Ou então você pode rodar o projeto com o Docker, para ser sincera, eu não o conhecia até pouco tempo atrás, mas estou estudando e assim que compreender plenamente como funciona, irei atualizar o readme. </i></li>
</ul>

### 📋 Pré-requisitos

<ul>
  <li>Node</li>
  <li>MySQL</li>
</ul>

## ⚙️ Executando os testes

Há um pequeno script de teste usando React.js, está localizado na pasta Client Side: riot/client/src/App.test.js

## 🛠️ Ferramentas e Tecnologias

<ul>
  <li>React (https://reactjs.org/) - Para componenetes no front e testes.</li>
  <li>Node.js (https://nodejs.org/en/) - Para a API.</li>
  <li>MySQL (https://www.mysql.com/) - Para o banco de dados da aplicação.</li>
  <li>Docker (https://www.docker.com/) - Para o container da aplicação.</li>
</ul>

<i> PS.: Estava a fazer um deploy da aplicação no Heroku (https://www.heroku.com/home), mas como a conexão com o BD MySQL exige o cartão de crédito ainda que tenha um plano FREE, estou procurando outra forma de subir a aplicação ou então passar a usar o Postgre. </i>

## 📌 Versão

<ul>
  <li>:heavy_check_mark: 1.0 - Template-base; Conexão com o banco; integrando o React.js com o Node.js; Introdução ao Docker; Insert e select</li>
  <li>:clock3: 2.0 - Pretendo: acrescentar mais funcionalidades no Front-end usando o React.js, upload de arquivos com Node.js, mais testes, consumir algum serviço em núvem</li>
</ul>

## ✒️ Autores

Luiza - Desenvolvedora web e estudante
