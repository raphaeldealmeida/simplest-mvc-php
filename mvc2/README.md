##Bem simples aplicativo usando PHP com MVC

###Vejamos os papeis dos componentes:

- Model - é onde a regra de negócios acontece. No caso de uma calculadora é aqui que os cálculos são feitos

- Controller - é i intermediário entre a view e o model, recebe as solicitações da view e passa para o model, então devolve para a view

- View - solicita um cálculo e ao receber mostra ao usuário

Estou considerando que a view não vai direto ao model, mas quem faz isso é o controller

Observe que tudo começa e termina no index.php

- O index.php instancia a view e chama seus métodos
- Então a view chama os respectivos métodos do controller
- O controller chama os respectivos métodos do model
- O model devolve para o controller
- O controller devolve para a view
- A view devolve para o index.php

##Quando a adoção do PSR-4

Ele casa os arquivos do diretório

app

Com o namespace

App

##Instalação

- Copiar esta pasta para seu documentroot
- Acesse o terminal/prompt e execute:
composer dump-autoload
- Chame a pasta pelo navegador

