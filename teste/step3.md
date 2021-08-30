Após implementado nosso arquivo Dockerfile, utilizaremos o comando ```docker build``` para construirmos nosso imagem.

Imagens são como virtual disks utilizados em máquinas virtuais, onde função é armazenar programas, bibliotecas, arquivos de configuração e código da nossa aplicação.

No caso, o Dockerfile criado anteriormente irá permitir criarmos uma imagem que se baseará na imagem php:7.4-apache.

Esta imagem está hospedada no Docker Hub, e será baixada automaticamente.

A partir do terminal a lado direito, execute:

-> Construindo nossa imagem (chamada webapp-img:v1)

`docker build -t webapp-img:v1 .`{{execute}}

-> Lista as imagens existentes no servidor:

`docker images`{{execute}}

A grande vantagens de imagens de containers, é que diferentemente discos virtuais, elas não armazenam um sistema operacional completo, mas apenas o que as aplicações do container realmente necessitam para funcionar adequadamente.
    
-> Clique no botão CONTINUE

