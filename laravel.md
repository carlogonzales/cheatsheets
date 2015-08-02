# LARAVEL

## Routing

### Basic Routing

    Route::get('/', function () {
        return 'Hello World';
    });

    Route::post('users/{id}', function ($id) {
        return $id;
    });

    Route::put('users/{id}', function ($id) {
        return $id;
    });

    Route::delete('users/{id}', function ($id) {
        return $id;
    });
    
### Multiple HTTP Verb

    Route::match(['put', 'post'], 'users/{id}', function ($id) {
        return $id;
    });

    Route::any('users/{id}', function ($id = null) {
        return $id;
    });