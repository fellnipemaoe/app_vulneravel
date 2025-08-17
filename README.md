Para instalar necessário ter o banco postgres e php 8.3 com PDO.

Criação da tabela do banco 

CREATE TABLE usuarios (
  id serial,
  usuario varchar(100),
  senha varchar(100)
)

Para apontar o servidor de banco altere o arquivo db.php
