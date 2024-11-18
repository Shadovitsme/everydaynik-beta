# EveryDaynik!

## How to run

```bash
git clone https://github.com/Shadovitsme/everydaynik-beta
cd everydaynik-beta
cp .env.example .env
sudo composer update
php artisan key:generate
npm install
sudo docker compose up -d
vendor/bin/sail artisan migrate:fresh
npm run build
```

Открыть в браузере `http://localhost:80/`