Этот проект был сделан для ознокомления и тестовых заданий.

Cmds:
curl -s "https://laravel.build/example-app" | bash
./vendor/bin/sail up

./vendor/bin/sail composer require laravel/ui
./vendor/bin/sail php artisan ui react
./vendor/bin/sail php artisan ui react --auth

./vendor/bin/sail npm install && npm run dev
./vendor/bin/sail npm run build