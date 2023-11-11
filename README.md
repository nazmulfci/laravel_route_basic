<p align="center"><a href="https://laravel.com" target="_blank"><img src="https://raw.githubusercontent.com/laravel/art/master/logo-lockup/5%20SVG/2%20CMYK/1%20Full%20Color/laravel-logolockup-cmyk-red.svg" width="400"></a></p>

<p align="center">
<a href="https://travis-ci.org/laravel/framework"><img src="https://travis-ci.org/laravel/framework.svg" alt="Build Status"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/d/total.svg" alt="Total Downloads"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/v/stable.svg" alt="Latest Stable Version"></a>
<a href="https://packagist.org/packages/laravel/framework"><img src="https://poser.pugx.org/laravel/framework/license.svg" alt="License"></a>
</p>



<p> Install Laravel  </p>
<p> php artisan make:controller UserController </p>
<p> Go to router folder > web.php </p>
<p> use App\Http\Controllers\UserController;
<br>
Route::get('/hello', [UserController::class, 'hello']); </p>

<p> Open the app/Http/Controllers/UserController.php file  </p>
<p> <?php

namespace App\Http\Controllers;

use Illuminate\Http\Request;

class UserController extends Controller
{
    public function hello()
    {
        return 'Hello, Laravel!';
    }
}
 </p>

 <p> Start the Laravel development server </p>
 <p> php artisan serve </p>

## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
#   l a r a v e l _ r o u t e _ b a s i c 
 
 
