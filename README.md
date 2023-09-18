# learnLaravel
 Synchronizing my learning process for laravel, a php framework
 *******************
Navigate to htdocs <br>
CREATE LARAVEL PROJECT
composer create-project laravel/laravel (appname)
<br>
GOTO FOLDER LOCATION
cd (appname)/
<br>
HOST LOCAL SERVER
php artisan serve
<br>
MAKE TABLE - CAN CHECK AT app-database-migration
php artisan make:migration create_(table name)_table
<br>
RUN/SEND TABLE TO DATABASE
php artisan migrate
<br>
MAKE MODEL
php artisan make:model (Classname)
<br>
PUT IN MODEL CODE - app-model
protected $fillable = ['var1', 'var2', ...];
<br>
MAKE CONTROLLER - app-http-controller
php artisan make:controller (ControllerName [ProductController])
<br>
CREATE FOLDER FOR ENTITY IN VIEW - RESOURCES>VIEWS
(for example add file index.blade.php)
<br>
ADD ROUTE IN routes-web.php
Route::get('/(uri cam product ke about ke)', [(NamaController)::class, '(functionName)'])->name("(entityname).index");
