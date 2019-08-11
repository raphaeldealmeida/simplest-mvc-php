##Bem simples aplicativo usando MVC

Estou considerando que a view não vai direto ao model, mas ao controller

Observe que tudo começa no index.php, que em nosso caso é a view

- A view chama o controller
- O controller chama os respectivos métodos do model
- O model devolve para o controller
- O controller devolve para a view

##Instalação
- Entre no terminal/prompt e execute:
`php -S localhost:3000 -t`
- Acesse o navegador http://localhost:3000



