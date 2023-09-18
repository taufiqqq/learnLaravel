# learnLaravel
 Synchronizing my learning process for laravel, a php framework
 *******************
Navigate to htdocs <br><br>
CREATE LARAVEL PROJECT<br>
composer create-project laravel/laravel (appname)
<br><br>
GOTO FOLDER LOCATION<br>
cd (appname)/
<br><br>
HOST LOCAL SERVER<br>
php artisan serve
<br><br>
MAKE TABLE - CAN CHECK AT app-database-migration<br>
php artisan make:migration create_(table name)_table
<br><br>
RUN/SEND TABLE TO DATABASE<br>
php artisan migrate
<br><br>
MAKE MODEL<br>
php artisan make:model (Classname)
<br><br>
PUT IN MODEL CODE - app-model<br>
protected $fillable = ['var1', 'var2', ...];
<br><br>
MAKE CONTROLLER - app-http-controller<br>
php artisan make:controller (ControllerName [ProductController])
<br><br>
CREATE FOLDER FOR ENTITY IN VIEW - RESOURCES>VIEWS<br>
(for example add file index.blade.php)
<br><br>
ADD ROUTE IN routes-web.php<br>
Route::get('/(uri cam product ke about ke)', [(NamaController)::class, '(functionName)'])->name("(entityname).index");
