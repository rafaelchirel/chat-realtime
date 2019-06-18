<p align="center"><img src="https://laravel.com/assets/img/components/logo-laravel.svg"><img src="https://vuejs.org/images/logo.png" width="197px" height="64px"></p>

## Requerimientos

- PHP >= 7.1.3
- MySQL
- Git
- Composer
- npm >= 3.10.10
- node >= 6.11.1

## Instalación

**Git**
```shell
git clone https://github.com/rafaelchirel/chat-realtime.git
```

**Crear Base de Datos**
```shell
DB_DATABASE=chat
```

**Copiar archivo .env.example asignandole por nombre .env**
```shell
Console linux
cp .env.example .env
```

**Localizar estas variables de entorno dentro del archivo `.env` y reasignarle estos nuevos valores**
```php
	DB_DATABASE=chat
	DB_USERNAME=root
	DB_PASSWORD=

	BROADCAST_DRIVER=pusher

	PUSHER_APP_ID=anyID
	PUSHER_APP_KEY=anyKey
	PUSHER_APP_SECRET=anySecret
```

**Dependencias**
```shell
php artisan migrate
php artisan key:generate
composer install
npm install
```

**iniciar**
```shell
	http://127.0.0.1:8000 o http://localhost:8000
```

## Colaborar

Cualquier aportación vía Pull-Request  :)
