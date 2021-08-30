Após construída nossa image, iremos disparar um novo container utilizando esta imagem.

A partir do terminal a lado direito, execute as ações:

-> Disparando um container utilizando a imagem chamada webapp-img:v1

`docker container run -d -p 80:80 -t webapp-img:v1`{{execute}}

-> Liste os containers atualmente em execução

`docker container ls`{{execute}}

-> Acessando nossa aplicação web via web client CURL. Além de acessarmos a aplicação iremos passar valores pela URL (método GET).
Deste modo, a aplicação receberá os valores 10 e 9, e estes serão armazenados nas variáveis dinâmicas (valor1 e valor2) que serão criadas no código PHP.

`curl "http://localhost?valor1=10&valor2=9"`{{execute}}

O resultado exibido é a média aritmética dos valores 10 e 9.
    
-> Clique no botão CONTINUE

