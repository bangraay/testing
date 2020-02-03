# Product/Project Name
Aplikasi GIS Aset merupakah Sistem berbasis peta untuk menampilkan informasi terkait aset Pemerintah Jawa Barat.

## System Architecture
- Backend ? (Laravel 5.7)
- Frontend ? (VUE JS 2.5.16)
- Authentication ? -
- Database ? postgre SQL
- Storage ? (S3, Minio)
- External services/API ? - 

## Setup Development
### Configuration
clone this repository using command “git clone https://username:password@gitlab.com/jdsteam/command-center-jawa-barat/comcen-app-gis.git”
create new gis_aset database
Import database
set .env or .env.example 

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=gis_aset
DB_USERNAME=db_user
DB_PASSWORD=db_password

### Migration & Database Seeding
-

### Running Development Local Server
clone this repository to your local server
create new gis_aset database
Import database
set .env or .env.example 

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=gis_aset
DB_USERNAME=db_user
DB_PASSWORD=db_password

composer install
npm install or npm i
php artisan optimize


### Running Test
-

## Deployment
clone this repository
create new gis_aset database
Import database
set .env or .env.example 

DB_CONNECTION=pgsql
DB_HOST=127.0.0.1
DB_PORT=5432
DB_DATABASE=gis_aset
DB_USERNAME=db_user
DB_PASSWORD=db_password

composer install
npm install or npm i
php artisan optimize

