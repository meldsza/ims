## WORK IN PROGRESS  

## About IMS

IMS is a web invoice management system built using Laravel

- Create custom invoices easily
- Integrate with EWay bill

## Setup  
#### Prerequisites
1. Git
2. PHP >7.3
3. MySQL/Postgres/SQLite/MSSQL
4. WebServer(Apache/Ngnix)

#### Downloading
Clone the Repository using git  

#### Installation  
1. Run `composer install` to install   
2. Run `php artisan key:generate` to generate application key
3. Edit the .env file according to your environment configuration
4. Run `php artisan migrate --seed`
5. Run `php artisan storage:link`
6. Run `php artisan optimize`

#### Updating    
1. Run `git pull`
2. Run `php artisan migrate`
3. Run `php artisan cache:clear`
4. Run `php artisan optimize`

## License

The IMS is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
