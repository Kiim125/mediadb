Repository clonen:

git clone https://github.com/Kiim125/mediadb.git

Compposer installieren:

composer install


.env Datei erstellen

```
cp .env.example .env
```

env anpassen --> eure Datenbank eintragen


App Key generieren:
```

php artisan key:generate
```

dann ein npm installieren:
```
npm install
```

dann
```
npm run dev
```

dann ein migrate machen:
```
php artisan migrate
```

dann die storage links erstellen:
```
php artisan storage:link
```
