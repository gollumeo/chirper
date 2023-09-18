<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400" alt="Laravel Logo"></a></p>

This is a simple project I built to learn how to use Vue.js 3 within Laravel 10. 
To do so, I've also been using Inertia.js to render my vue components. 

## Installation

Clone this repository and install all the dependencies
```bash
git clone https://github.com/gollumeo/chirper.git
npm install
composer install
```

Once set up, copy the .env.example into .env 
```bash
cp .env.example .env
```

Then, get comment your DB environment since we're using SQLite and change this line: 
```.env
DB_CONNECTION=sqlite
```

## Run the environment

Simply run the environment as you'd do in any Laravel project: 
```bash
php artisan serve
npm run dev
```

Have fun with your chirps now! 
