A partir do terminal a lado direito, execute:

-> Instalação do editor de texto mcedit
    apt install mc -y

-> Crie um diretório chamado webapp1
    mkdir webapp1

-> Acesse/abra o diretório criado
    cd webapp1

-> Crie o arquivo index.hp
    mcedit index.php

-> Digite o código a seguir:

    <?php
      $num1=$_GET['valor1'];
      $num2=$_GET['valor2'];
      $media=($num1+$num2)/2;
      echo "A media dos valores: ".$media;
    ?>

-> Pressione F10, e com as setas de direção, selecione "YES" e pressione ENTER

-> Verifique se o arquivo foi criado:
    ls -l
    
-> Clique no botão CONTINUE
