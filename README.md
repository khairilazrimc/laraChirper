<p align="center">A project built using the Laravel Framework</p>
<p align="center"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="313" alt="Laravel Logo"></p>

<br>

## About LaraChirper

LaraChirper is a project developed based on Laravel [Bootcamp](https://www.youtube.com/watch?v=MYyJ4PuL4pY) and [this video](https://www.youtube.com/watch?v=MYyJ4PuL4pY) posted by PHP Annotated.

It is built as a twitter-like application that intends to record, manage, and display messages (Chirps) posted by registered users (Chirper). 

<br>

## LaraChirper Use-Case

Guest
- Register as a Chirper
- Login to Chirper account

Chirper
- View all Chirps
- Post/Create Chirps
- Edit/Update posted Chirps
- Delete posted Chirps
- Logout from Chirper account

<br>

## Within LaraChirper

This project utilizes the Laravel v9 **framework** with inclusion of Vue.js to catter for the front-end views, glued together using InertiaJS. Below are the other framework that are also used in this project:
- npm install dayjs - to convert time and date details to more user readable details.
- composer require spatie/laravel-mail-preview - to view mail sent by the system
- composer require laravel/breeze --dev - to supply the application with a complete authentication system - php artisan breeze:install
- npm run dev - to build the view from Vue.js

This project only make use of 2 **controllers**, named ChirpController.php and ProfileController.php(Breeze) which can be found inside //app/Http/Controllers/. Inside these controller, several basic functions have been declared:
- page rendering using Inertia JS
- show all Chirps 
- form validation
- object creation/edit/delete
- user authentication
- user profile update/delete
- user registration/login/logout

This project only have 2 **models** which are Users.php (have many Chirp) and Listing.php (belongs to User) which can be found inside //app/Models/. Inside these models several basic functions have been declared:
- protected data
- object relationship

This project utilizes Vue.js to make up its **view**:
- breeze  - resources/js/Components/
- breeze  - resources/js/Layouts/
- breeze  - resources/js/Pages/Auth/
- index   - resources/js/Pages/Chirps/
- breeze  - resources/js/Pages/Profile/
- breeze  - resources/js/Pages/Profile/Partials

This project utilizes SqlLite **database**. This repo encompasses the required factories and migrationsfiles which can be executed as to showcase the initial built of this application.

Last but not least, the project was build using these **version** of frameworks:
- PHP 8.2.0
- Laravel 9.48.0
- Composer 2.5.1
- Laravel Breeze 1.18
- NPM 8.19.3
- Vite 4.0.4 - plugin 0.7.3\

So with that, I humbly thank you.
