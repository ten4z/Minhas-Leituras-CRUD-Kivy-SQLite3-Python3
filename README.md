# Minhas-Leituras-CRUD-Kivy-SQLite3-Python3
Organizador de Leituras, nunca mais se perca nas leituras de seus livros favoritos, um App Cross-Platform

CREATE - Insira seus Livros, Autor Quantidade de Páginas e Data de Leitura

READ - Seleciona o registro na base de dados

UPDADE - Atualiza o registro no banco de dados

DELETE - Exclui o registro pelo id passado como parâmetro

CRUD completo e funcional com tecnologia de persistência de dados
Projeto orientado a objetos com a syntax do Kivy Framework

Possui basicamente três arquivos:

'gui.kv': este arquivo consiste na interface gráfica de usuário

'main.py': outro arquivo para o código principal 

'org_livros.db': um terceiro arquivo para a base de dados.


Meu artigo sobre este repositório:
http://josielsoares.com/artigos/kivy/crud-completo-em-kivy-e-sqlite3.php

Estrutura da Tabela:
sql = """ CREATE TABLE IF NOT EXISTS tb_livros( id INTEGER PRIMARY KEY AUTOINCREMENT, titulo TEXT (50) NOT NULL, autor TEXT (50), data_leitura DATE, pagina_atual INTEGER, n_paginas INTEGER)"""

Com o Kivy este mesmo projeto pode ser compilado para ser executado em:
Windows, Linux, MacOS, Iphone, Android, Raspberry Pi 
