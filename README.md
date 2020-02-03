# Aplikasi GIS Aset
Aplikasi GIS Aset merupakah Sistem berbasis peta untuk menampilkan informasi terkait aset Pemerintah Jawa Barat.

## System Architecture
- Backend (Laravel 5.7)
- Frontend (VUE JS 2.5.16)
- Database (postgre SQL)
- Storage (Minio) 

## Setup Development
### Configuration
```bash
# clone this repository using command “git clone https://username:password@gitlab.com/jdsteam/command-center-jawa-barat/comcen-app-gis.git”
# create new gis_aset database
# Import database
# set .env or .env.example 
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=gis_aset
DB_USERNAME=db_user
DB_PASSWORD=db_password
```
### Migration & Database Seeding
-

### Running Development Local Server
```bash
# clone this repository using command “git clone https://username:password@gitlab.com/jdsteam/command-center-jawa-barat/comcen-app-gis.git”
# create new gis_aset database
# Import database
# set .env or .env.example 
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=gis_aset
DB_USERNAME=db_user
DB_PASSWORD=db_password

# composer install
# npm install or npm i
# php artisan optimize
```
### Running Test
-

## Deployment
```bash
# clone this repository
# create new gis_aset database
# Import database
# set .env or .env.example 
DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=gis_aset
DB_USERNAME=db_user
DB_PASSWORD=db_password

# composer install
# npm install or npm i
# php artisan optimize
```

