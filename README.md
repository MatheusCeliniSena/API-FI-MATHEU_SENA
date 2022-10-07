# API-FI-MATHEU_SENA

1) Primeiramente temos que instalar as dependencias
  npm install
  npm init -y
  npm init
  
2) Depois fazer a conexão com o banco de dados postgresql
    user: 'postgres',
    host: 'localhost',
    database: 'Faculdade',
    password: 'postgres',
    port: '5432'
    
3) Por fim só iniciar a API

  node src/app.js
  
4) E passar as rotas

  GET:  /getFilmes
  POST: /postFilmes
  PUT: /putFilmes
  DELETE: /deleteFilmes
