fortune-frases-pt-br
====================

Bases de frases para utilização com o fortune

O programa [fortune](http://en.wikipedia.org/wiki/Fortune_%28Unix%29) 
exibe frases aleatórias provindas de uma base de dados.

Este repositório conterá bases para frases em português.

    wget https://github.com/edusantana/fortune-frases-pt-br/archive/master.zip && unzip master.zip

E para executar escolha uma base:
    cd fortune-frases-pt-br-master
    fortune espiritas

Para edicionar novas frases basta editar os arquivos as mensagens.

## Rake Tasks

Depois que novas mensagens forem adicionadas é necessário atualizar
a base de dados (os arquivos `.dat`):

    rake compile

## Você está convidado a adicionar novas mensagens

Edite os arquivos no github e crie um pull request.

