O arquivo Dockefile permite implementar um arquivo de parâmetros, onde cada instrução dele derminará como nossa imagem será construída.

A partir do terminal a lado direito, execute:

-> Crie o arquivo Dockerfile (observação: D maiúsculo):

`mcedit Dockerfile`{{execute}}

-> Digite o código a seguir:

```
FROM php:7.4-apache
COPY index.php /var/www/html
```

-> Pressione ```F10```, e com as setas de direção, selecione "YES" e pressione ENTER

-> Verifique se o arquivo foi criado:

`ls -l`{{execute}}
    
-> Clique no botão CONTINUE
