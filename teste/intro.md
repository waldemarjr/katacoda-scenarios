Os objetivos desta atividade são:

- Criar uma aplicação PHP para ser testada em nosso web server (arquivo index.php)
- A aplicação PHP irá receber via URL (método GET) dois valores e devolver ao usuário (no terminal) a média de ambos valores

- Criar um arquivo de parametrização (Dockerfile) que permitirá:
  - Criar uma imagem contendo o software web server Apache com suporte a PHP 7.4
  - Copiar o arquivo index.php para dentro da imagem

- Construir nossa imagem (Apache com suporte a PHP 7.4) + arquivo index.php

- Disparar um container utilizando a imagem recém construída.

- Acessar a aplicação PHP hospedada no container por meio do web client CURL.
