# Learning Laravel 11

## Estrutura

-vite.config.js -> Ajuda na compilação de arquivos estáticos

-phpunit.xml -> aplicação de testes

-packege.json -> JS / -composer.json -> PHP

-artisan -> comando *php artisan* mostra todas as funcionalidades

-editorconfig -> configurações dos arquivos, espaçamentos padrões, identação, etc.

-storage -> mais utilizado em ambiente local, armazena logs, caches.

-routes -> 
    console -> criar comandos e automatizar tarefas no projeto
    web -> rotas do projeto

-resources -> arquivos estáticos (css/js/views)

-public -> arquivos com permissão de acesso público

-database ->
    migrations -> estruturas de tabela
    factories -> cria valores "fakes" para testes
    seeders -> cria um usuário com valores específicos

-config -> configurações iniciais da aplicação

-bootstrap ->
    app -> configurações de rotas, middlewares, exceptions
    providers -> configura os provedores do projeto (/app/providers)

app -> 
    Providers -> cria classes, dependencias, definir recursos para start da aplicação, outros
    Models -> Modelos de representação das tabelas e relações entre elas
    Http/Controllers -> Controlador onde ficam as funções onde são add/alterados valores as tabelas 


