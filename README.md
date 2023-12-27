<p align="center"><img src="https://laravel.com/img/logotype.min.svg" width="400"></p>

Daftar/Register admin dengan url `/register-admin`. Secret key dapat diubah di env atau default "Secret123".

Login admin:  
Email : admin@laundryxyz.com  
Pass : admin123

## Instalasi
1. Bikin database kosongan dina phpmyadmin 
1. Konfigurasi .env ganti DB_DATABASE jadi ngaran database nu bieu di jieun
3. ketik dina terminal vscode:

```
php artisan key:generate
php artisan migrate:fresh --seed
```

ke langsung aya tabel an database kosongan na