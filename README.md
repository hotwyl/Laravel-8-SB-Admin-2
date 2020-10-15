<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
[![Github Badge](https://img.shields.io/badge/-Github-000?style=flat-square&logo=Github&logoColor=white&link=https://github.com/fagnerpsantos)](#)
[![Linkedin Badge](https://img.shields.io/badge/-LinkedIn-blue?style=flat-square&logo=Linkedin&logoColor=white&link=https://www.linkedin.com/in/fagnerpsantos/)](#)
[![Twitter Badge](https://img.shields.io/badge/-Twitter-1ca0f1?style=flat-square&labelColor=1ca0f1&logo=twitter&logoColor=white&link=https://twitter.com/fagnerpsantos)](#)
[![Youtube Badge](https://img.shields.io/badge/-YouTube-ff0000?style=flat-square&labelColor=ff0000&logo=youtube&logoColor=white&link=https://www.youtube.com/user/TreinaWeb)](#)
<a href="#"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="#"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="#"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="#"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>

# Painel Adinistrativo para [Laravel](https://laravel.com/docs/) com [SB Admin v2](https://startbootstrap.com/themes/sb-admin-2/)

> Este projeto é parte do famoso tema [SB Admin v2](https://startbootstrap.com/themes/sb-admin-2/) desenvolvido em [Bootstrap 4](https://getbootstrap.com/docs/) para o popular Framework [Laravel em sua versão 8.x ou 7.x.](https://laravel.com/docs/) Cada estrutura de design do SB Admin é dividida em componentes e slots.

- Saiba mais no [site do Tema](https://startbootstrap.com/themes/sb-admin-2/)
- Saiba mais na [documentação do Framework](https://laravel.com/docs/)
- Saiba mais na [documentação da Bibliotáca](https://getbootstrap.com/docs/4.5/getting-started/introduction/)

## Requisitos

> Este modelo de administração usa o framework Laravel. Se você estiver recebendo algum erro, provavelmente é devido a requisitos não atendidos da própria estrutura.

- PHP >= 7.4.0
- BCMath PHP
- Ctype PHP
- JSON PHP
- Mbstring PHP
- OpenSSL PHP
- PDO PHP
- Tokenizer PHP
- XML PHP
- MySQL
- [Node.js and NPM](https://docs.npmjs.com/getting-started/installing-node)
- [Yarn](https://yarnpkg.com/en/docs/install)
- [Node.js](https://nodejs.org/en/download/)
- [composer](https://getcomposer.org/download/)

## Instalação

- Clone o repositório e `cd` acesse o mesmo
- Execute o comando `composer install`
- Copie e Renomei `.env.example` O arquivo `.env`
- Execute `php artisan key:generate`
- Defina suas credenciais de banco de dados no arquivo `.env`
- Execute `php artisan migrate`

### Passo a Passo

1. Clone este projeto ou baixe o arquivo ZIP
`git clone <project-repository>` 

2. Em seu terminal (prompt de comando), execute os seguintes comandos:

`cd <project-directory>` Acesse  o diretório do projeto

`composer install` Instale os pacotes necessários

`npm install` Instale dependências adicionais

`copy .env.example .env` Crie o arquivo .env copiando o arquivo .env.example

`php artisan key:generate` Gerar uma chave, pois este é um projeto clonado

`php artisan migrate` Cria as Tabelas na base de dados definida no arquivo `.env`

`npm run watch` Monitor de alteração (Optional)

`php artisan cache:clear` Limpar cache (Optional)

`php artisan serve` Execute o servidor do Framework

3. Acesse `http://localhost:8000` em seu navegador de Internet

## Notas

> È recomendado Utilizar os processos deste projeto ao inicio do seu projeto. 
> Estes procedimentos poderam neutralizar seus designes e ocasionar falhas em seu projeto.

## Créditos

Laravel SB Admin 2 usa algumas bibliotecas e pacotes de terceiros. Agradecimentos à comunidade web.

## Referências

- [Alejandro RH - aleckrh](https://github.com/aleckrh/laravel-sb-admin-2)
- [Avatar Sagar Chamling - cham11ng](https://github.com/cham11ng/sbadmin-laravel)

## Preview

`login`

<!---
<img src="https://imgur.com/YjGp6Sbl.png">
-->

***

`register`

<!---
<img src="https://imgur.com/Wj09cu4l.png">
-->

***

`dashboard`

<!---
<img src="https://imgur.com/CrmOfT5l.png">
-->

***

`profile`

<!---
<img src="https://imgur.com/5t4eS1rl.png">
-->

***

`logout`

<!---
<img src="https://imgur.com/d9JclOYl.png">
-->

## Como Utilizar

Ao criar views basta estender os Layouts correspondente da pasta `Layouts` e segir as orientações de `@extends` e `@section` para arquivos `.blade` segundo documentação [Laravel](https://laravel.com/docs/)

Você Também poderá criar suas próprias paginas com layout personalisados utilizando [Bootstrap](https://getbootstrap.com/docs/) 

## Licença

Licenciado sob a licença MIT.

## Ferramentas Sugeridas para uso

- Terminal Texto - [Git](https://gitforwindows.org/)
- Terminal Texto - [Comander](https://cmder.net/)
- IDE Desenvolvimento - [Sublime Text](https://www.sublimetext.com/)
- IDE Desenvolvimento - [Visual Studio Code](https://code.visualstudio.com/)
- IDE Desenvolvimento - [NetBeans](https://netbeans.org/)
- IDE Desenvolvimento - [Atom](https://atom.io/)
- Editor de Código - [Notepad++](https://notepad-plus-plus.org/)
- Emulador de Serviços Web - [Xampp](https://www.apachefriends.org/pt_br/index.html)
- Emulador de Serviços Web - [WampServer](https://www.wampserver.com/en/)
- Gerenciado de Banco de Dados - [Workbench](https://www.mysql.com/products/workbench/)
