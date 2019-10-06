.. Servidor de Desafios

Overview
**************************

O que é?
==========================

Trata-se de um projeto desenvolvido pelo professor Raul Ikeda
para a matéria de design de software do primeiro semestre
do Insper.

O projeto possibilita que os alunos desenvolvam ou façam o upload
de soluções para problemas de sala de aula, o qual, por sua vez
é rodado em um lambda da AWS onde é avaliado.

Instalação
==========================

O projeto foi realizado em Python 3, utilizando uma DB em SQLite 3
(a qual já faz parte da biblioteca padrão do próprio python 3)

Além disso, o projeto depende das seguintes bibliotecas externas:

* Flask
* flash_httpauth

Uso
==========================

Por fim, para executar o projeto, é necessário criar um arquivo
user.csv, e rodar o script adduser.py, o qual criará os usuários
descritos a partir do csv.

O padrão do csv é que cada linha contenha o usuário de um aluno
e o seu tipo (sendo que usuários chamados "fabioja" ou com o tipo)
admin terão permissões especiais.

Documentação
**************************
.. toctree::
   :maxdepth: 2
   :caption: Contents:


ServidorSoftDes main
=======================================
.. automodule:: softdes
    :members:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
