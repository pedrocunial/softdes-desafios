.. Pedro Cunial documentation master file, created by
   sphinx-quickstart on Tue Oct  1 08:04:39 2019.
   You can adapt this file completely to your liking, but it should at least
   contain the root `toctree` directive.

Welcome to Pedro Cunial's documentation!
========================================

.. toctree::
   :maxdepth: 2
   :caption: Contents:

ServidorSoftDes main
=======================================

H1 -- Servidor De Desafios
**************************

H2 -- O que é?
==========================

Trata-se de um projeto desenvolvido pelo professor Raul Ikeda
para a matéria de design de software do primeiro semestre
do Insper.

O projeto possibilita que os alunos desenvolvam ou façam o upload
de soluções para problemas de sala de aula, o qual, por sua vez
é rodado em um lambda da AWS onde é avaliado.

H2 -- Instalação
==========================

O projeto foi realizado em Python 3, utilizando uma DB em SQLite 3
(a qual já faz parte da biblioteca padrão do próprio python 3)

Além disso, o projeto depende das seguintes bibliotecas externas:

* Flask
* flash_httpauth

H2 -- Uso
==========================

Por fim, para executar o projeto, é necessário criar um arquivo
user.csv, e rodar o script adduser.py, o qual criará os usuários
descritos a partir do csv.

O padrão do csv é que cada linha contenha o usuário de um aluno
e o seu tipo (sendo que usuários chamados "fabioja" ou com o tipo)
admin terão permissões especiais.

ServidorSoftDes softdes
=======================================
.. automodule:: softdes
    :members:



Indices and tables
==================

* :ref:`genindex`
* :ref:`modindex`
* :ref:`search`
