# Dicoding Submission Belajar Jaringan Komputer untuk Pemula

### Nginx
Untuk menggunakan konfigurasi NGINX 

1. Install NGINX mengunakkan command:
```
sudo apt install nginx -y
```

2. Salin file `konfigurasiNGINX_MohammadRaska.txt` ke directory `/etc/nginx/sites-available/default`

3. Restart dan pastikan service Nginx berjalan dengan command:
```
sudo systemctl restart nginx
sudo systemctl status nginx
```

### Apache2
Untuk menggunakan konfigurasi Apache2 

1. Install Apache2 menggunakan command:
```
sudo apt install apache2 -y
```

2. Salin file `konfigurasiApache2_MohammadRaska.txt` ke directory `/etc/apache2/sites-available/000-default.conf` dan file `ports_MohammadRaska.txt` ke directory `/etc/apache2/ports.conf`

3. Aktivasi module proxy pada Apache2 dengan command:
```
sudo a2enmod proxy proxy_http proxy_balancer lbmethod_byrequests
``` 

4. Restart dan pastikan service Apache2 berjalan dengan command:
```
sudo systemctl restart apache2
sudo systemctl status apache2
```

### NodeJS App

Untuk menjalankan project ini, pastikan `npm` sudah terinstall pada komputer/laptop Anda.

---

Tata cara menjalankan project:

1. Install node modules

```
npm install
```

2. Jalankan project

```
npm run start
```


### Referensi

Tautan referensi yang membantu pekerjaan 
[Dicoding - Belajar Jaringan Komputer untuk Pemula](https://www.dicoding.com/academies/387/tutorials/23123)
[How To Use Apache as a Reverse-Proxy with mod_proxy on Ubuntu 20.04](https://www.digitalocean.com/community/tutorials/how-to-use-apache-http-server-as-reverse-proxy-using-mod_proxy-extension-ubuntu-20-04)

