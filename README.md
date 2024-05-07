<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/dt/laravel/framework" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/v/laravel/framework" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://img.shields.io/packagist/l/laravel/framework" alt="License"></a>
</p>

## About Laravel

Laravel is a web application framework with expressive, elegant syntax. We believe development must be an enjoyable and creative experience to be truly fulfilling. Laravel takes the pain out of development by easing common tasks used in many web projects, such as:

- [Simple, fast routing engine](https://laravel.com/docs/routing).
- [Powerful dependency injection container](https://laravel.com/docs/container).
- Multiple back-ends for [session](https://laravel.com/docs/session) and [cache](https://laravel.com/docs/cache) storage.
- Expressive, intuitive [database ORM](https://laravel.com/docs/eloquent).
- Database agnostic [schema migrations](https://laravel.com/docs/migrations).
- [Robust background job processing](https://laravel.com/docs/queues).
- [Real-time event broadcasting](https://laravel.com/docs/broadcasting).

Laravel is accessible, powerful, and provides tools required for large, robust applications.

## Learning Laravel

Laravel has the most extensive and thorough [documentation](https://laravel.com/docs) and video tutorial library of all modern web application frameworks, making it a breeze to get started with the framework.

If you don't feel like reading, [Laracasts](https://laracasts.com) can help. Laracasts contains over 1500 video tutorials on a range of topics including Laravel, modern PHP, unit testing, and JavaScript. Boost your skills by digging into our comprehensive video library.

## Code of Conduct

In order to ensure that the Laravel community is welcoming to all, please review and abide by the [Code of Conduct](https://laravel.com/docs/contributions#code-of-conduct).

If you discover a security vulnerability within Laravel, please send an e-mail to Taylor Otwell via [taylor@laravel.com](mailto:taylor@laravel.com). All security vulnerabilities will be promptly addressed.

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).

## Aknowledgement

The ISPM Laravel Project is open-sourced for "New Recruitment - IS Lab Website" project using Laravel. If you need help with this project, kindly hit me on mail at admin@naspadstudio.my.id!


## Docker Ready :D

To install docker with this project

First, build the docker image using `docker build <buildpath> -t ispmlaravel`

Then, run `docker run -d -p 81:8000 --name backend ispmlaravel`

Voila! Happy coding :D

### What To Do (For New Install)

1. Remove ignored files from your local repository
    
    To **maintain consistency** in future commits and **prevent repository bloat**, it's essential to exclude the node_modules and vendors directory from version control.
    
    ⚠️ Ensure that your **.env** files are functioning correctly, as the following command will remove them from version control tracking, based on the **.gitignore** configuration.
    
    ```bash
    # Remove the files from the index (not the actual files in the working copy)
    $ git rm -r --cached .
    
    # Add these removals to the Staging Area...
    $ git add .
    
    # ...and commit them!
    $ git commit -m "Clean up ignored files"
    ```
    

1. Install required NPM packages
    
    ```bash
    # on project root path, open your terminal
    $ npm install
    ```
    

1. Customization of css, js, and sass files
    
    If you need to add CSS, JS, or Sass files to customize the app, please place them in the respective folders located in resources/. Then, execute the following command each time you make changes to the resources assets.
    
    ```bash
    # on project root path, open your terminal
    $ npm run dev
    ```
