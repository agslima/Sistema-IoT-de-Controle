[![license](https://img.shields.io/github/license/agslima/Sistema-IoT-de-Controle?style=flat-square)](https://raw.githubusercontent.com/agslima/Sistema-IoT-de-Controle/master/LICENSE)

# Sistema de Controle IoT

Sistema para controle de entrada e saída de usuário, implementado em RaspberryPi com conceitos em IoT.

O objetivo do mini sistema é a criação e identificação do usuário com senhas criptografadas. O mini sistema é escrito com linguagem Python, usando e usada criptografia MD5 para salvar os usuários e senhas em um arquivo CSV.

### Sistema
O mini sistema tem os seguintes scripts em python:

- main_system.py Contém a main do sistema, ou seja, é o script principal do sistema.
- function.py: contém todas as funções do sistema; para mais detalhes, leia a parte de
documentação das funções.
- add_user.py: contém a funcionalidade de inserir ou deletar usuários no sistema.
- bad_password.py: script com a funcionalidade de criar senhas quem não devem ser usadas ao criar um novo usuário.

### Bibliotecas
Bibliotecas usadas:

https://github.com/intel-iot-devkit/mraa/blob/master/docs/building.md

https://learn.sparkfun.com/tutorials/installing-libmraa-on-ubilinux-for-edison/all
