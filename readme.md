# Sasaya Hello World

## Installation

Append Sasaya Hello World service provider to `providers` array in `config/app.php`.

```php
'providers' => [
    /*
     * Laravel Framework Service Providers...
     */
    Illuminate\Foundation\Providers\ArtisanServiceProvider::class,
    ...

    /*
     * Application Service Providers...
     */
    App\Providers\AppServiceProvider::class,
    ...

    /*
     * Sasaya Service Providers...
     */
    Sasaya\HelloWorld\Providers\ServiceProvider::class,
],
```
