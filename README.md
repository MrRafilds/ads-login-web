# ads-login-web

Projeto de Login Web utilizando a linguagem PHP no ambiente de desenvolvimento NetBeans.



**Requisitos iniciais:**

• Apache PHP – Pode usar o XAMPP

• Apache NetBeans – Pode usar qualquer editor de preferência;



**Criando as Páginas do Sistema**

Além da página inicial “index.php”, serão criadas também as páginas “menu.php” e

“logout.php”.

A página index.php irá incluir os campos referentes ao formulário para que um usuário possa

logar no sistema.



**Criação da Base de Dados de Exemplo**

Para o nosso exemplo criaremos uma base de dados, chamada "pweb" e criaremos também uma

tabela chamada Usuário. Para isso usaremos os seguintes comandos:



\#Criação da base de dados

create database pweb;



\#Definir o uso da base

use pweb;



\#Criação da tabela Usuario

create table usuario(

cod integer primary key auto\_increment,

nome varchar(50),

login varchar(20),

senha varchar(32));

