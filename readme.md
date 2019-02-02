<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

## Instruções do Desafio

<p> 1) Criar um formulário com pelo menos um campo de cada tipo: texto, senha, área de texto, select, checkbox, radio, botões (submit e reset).</p>
<p> a) Mostrar mensagem de erro até que todos os campos sejam preenchidos, com validação em JavaScript. </p>
<p> b) Mostrar mensagem de confirmação com as informações digitadas/escolhidas pelo usuário. </p>
<p> c) Validar usuario e senha com as informações de um arquivo 'autenticacao.json. </p>
<p> d) Pesquise e teste uma forma de armazenar e validar uma senha cifrada. </p>
<p> e) Demonstre conhecimento em CSS estilizando o formulário. </p>

## Instruções de Inicialização de Projeto


Clone o projeto do github

    $ git clone https://github.com/thafilakrumf/Desafio_Rota.git

Instale o composer dentro do projeto com o comando

    $ composer install

Renomeie ou copie e cole .env.exemple para .env.

Crie um banco de dados MySQL com o nome "desafio_rota".

No arquivo .env 
edite as seguintes linhas de código para conectar com o banco de dados

    DB_DATABASE=desafio_rota
    /* Suas credenciais de conexão com o banco de dados */
    DB_USERNAME=root
    DB_PASSWORD=root

Prosiga com o comando para gerar a autenticação do Laravel

     $ php artisan key:generate

Para iniciar o projeto no server do PHP rode o comando

    $ php artisan serve

Acesse o projeto na rota 

    localhost:8000

## License Laravel 5.7

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
