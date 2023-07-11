## Blog Multi Tenant

Nosso objetivo é criar uma aplicação de blog versátil e escalável, capaz de acomodar múltiplos usuários e seus respectivos blogs. Cada usuário terá a liberdade de criar e gerenciar seu conteúdo de forma independente.

A aplicação oferecerá um ambiente seguro para os usuários se registrarem, autenticarem e criar seus próprios blogs. Cada blog será associado a um subdomínio exclusivo que permitirá aos usuários compartilhar sua identidade única na web

Link das vídeo aulas: https://www.youtube.com/watch?v=EbrYqqxsTUM&list=PL_jABxon_0G41bH_F1onWFQw69_d03Ifr&pp=gAQBiAQB

## Comandos executados:

### Criar projeto do zero:
```bash
composer create-project --prefer-dist laravel/laravel blog
composer require laravel/breeze --dev
php artisan breeze:install --dark
php artisan migrate
php artisan serve
```

### Clonando repositório:
```bash
git clone ...
composer install
php artisan migrate
npm install
npm run dev
php artisan serve
```
