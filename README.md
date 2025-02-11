# Info Box
This template was created to make the WebApp developing process simple and accessible to everyone who loves the [Laravel]([url](https://laravel.com/)) and [Vue.js]([url](https://vuejs.org/)). 
The core of the entire sistem is [Inertia.js]([url](https://inertiajs.com/)), which it let you build a WebApp without creating an API. I also chose to integrate tailwindcss for a better experience in customizing the web app. To install it locally, here are the following steps:

# Requirements
<li>WLS2 or Linux or MacOS</li>
<li>PHP and Node.js (8.2 and v18 at least)</li>
<li>Composer and npm</li>
<li>git</li>

#Installation
After cloning the repository in your local enviroment, the installation process is quite simple:
Installing all the composer adn node dependencies
<li><code>composer install</code></li>
<li><code>npm install</code></li>

Setting up your Enviroment file .env
<li>First, create the file from the given example by Laravel <code>cp .env.example .env</code></li>
<li>
    Fill your file with your setup. If you don't know how, this is a simple example of a base mysql database configuration:
    
    ```
    DB_CONNECTION=mysql         //your database connection
    DB_HOST=127.0.0.1           //your databse host, 
    DB_PORT=3306
    DB_DATABASE=laravel
    DB_USERNAME=root
    DB_PASSWORD=
    ```
</li>
