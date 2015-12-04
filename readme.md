# Sasaya Hello World

## Installation

Run the composer require command:

```bash
compsoer require sasaya/helloworld
```

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

## Getting Started

Run the artisan command:

```bash
php artisan serve
```

Then we can open a browser and type `http://localhost:8000` and we would see `Hello World`.
