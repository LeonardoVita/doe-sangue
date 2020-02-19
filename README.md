# doe-sangue
Projeto MaratonaDev 3 rocketseat

##Instalação do Bando de Dados

Baixe no site oficial e instale o [PostgreSQL](https://www.postgresql.org/download/)

Baixe e instale o cliente visual [PostBrid](https://www.electronjs.org/apps/postbird) para manipular os bancos e as tabelas.

- crie um banco de dados chamado "doe"
- crie uam tabela chamada "donors"
- adcione 3 campos do tipo texto ('name','email','blood')

Configure com os dados do banco no arquivo server.js

    const db = new pool({ 
  
    user: 'postgres',   //seu nome de usuario
    
    password: '0000',   //seu password cadastrado
    
    host: 'localhost',  //host de acesso ao banco de dado
    
    port: 5432,         //a porta de comunicação com o BD
    
    database: 'doe'     //o nome do banco de dados criado 
    
    })
