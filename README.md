<h1 align="center">Encurtador de URL</h1>
<p align="center">

O Encurtador de url, além de fornecer uma url menor, nos possibilita acessar alguns dados sobre a nova URL gerada.

<h4>Como utilizar?</h4>

- Acessar o link : https://s-encurtador.herokuapp.com/
- Adicionar a URL que deseja encurtar
- Será gerada uma URL reduzida
- Essa URL será salva no banco de dados
- Para acessar as estatísticas da url basta adicionar ao final '/stats'

Exemplo de uso:

- Link a ser encurtado : www.google.com.br
- Link gerado: https://s-encurtador.herokuapp.com/QgxLV
- Dados do link : https://s-encurtador.herokuapp.com/QgxLV/stats
  
Para rodar em sua maquina basta:
  
- Clone este repositório: <i>$ git clone https://github.com/Sergiios/encurtador-url.git</i>
- Instale as dependências: <i>$ npm install</i>
- Altere a variavel DOMAIN no documento .env para http://localhost:3000/
- Execute a aplicação: <i>$ npm start</i>
- A aplicação vai funcionar em http://localhost:3000/

<h4>Tecnologias usadas:</h4>
<ul>
  <li> Nodejs </li>
  <li> Express </li>
  <li> Bootstrap </li>
  <li> EJS </li>
  <li> SQLite </li>
</ul>

</p>
