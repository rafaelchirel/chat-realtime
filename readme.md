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
composer install
npm install
php artisan key:generate
php artisan migrate
```

**iniciar**
```shell
	Abrir dos terminales

	En una de ella insertar este comando
	php artisan websockets:serve

	En la siguiente terminal, esté siguiente
	php artisan serve

	Desde el navegador web:
	http://127.0.0.1:8000 o http://localhost:8000
```

**Consideraciones**
```shell
	1)Abrir dos (2) pestañas en el navegador, una modo normal y otra modo incognito

	2)Luego acceder a la direccion siguiente para el registro, realizar proceso en cada pestaña
		http://127.0.0.1:8000/register

	3)URL Chat
	http://127.0.0.1:8000/chats o http://localhost:8000/chats
```

## Colaborar

Cualquier aportación vía Pull-Request  :)
