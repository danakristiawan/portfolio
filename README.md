# PORTFOLIO

## Installation Instruction
- git clone
- cd portfolio
- composer update
- cp .env.example .env
- php artisan key:generate
- touch database/database.sqlite
- php artisan migrate
- php artisan tinker
- use App\Models\User
- User::all()
- User::create(['name'=>'', 'email'=>'', 'password'=>'', 'google_id'=>'', 'avatar'=>''])
- User::first()
- open https://console.cloud.google.com/, create API Credential
- edit .env insert client_id and client_secret
- php artisan serve
