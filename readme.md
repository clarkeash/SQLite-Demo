## Demo

===

### Step 1

Install new laravel app

```composer create-project laravel/laravel SQLite-Demo```

### Step 2

```cd SQLite-Demo```

add sqlite

```touch storage/database.sqlite```

set sqlite to the driver in ```config/database.php```

### Step 3

run migrations

```php artisan migrate```

### Step 4

Add forms and endpoints (you can add your own)

see commit - https://github.com/clarkeash/SQLite-Demo/commit/2719a24cb0e0ce0f445b6f0192ef835e01cc4667

### Step 5

Add message to loggedin users - https://github.com/clarkeash/SQLite-Demo/commit/ef4baee99c7bc5a21824735743af3a5bc9e10746

### Step 6

Run server

```php artisan serve```

Register - http://localhost:8000/auth/register (on success you will hit a 404 page)
Login - http://localhost:8000/auth/login (you should see "Hello YOUR NAME"
Logout - http://localhost:8000/auth/logout

