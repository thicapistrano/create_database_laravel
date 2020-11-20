# Create Laravel Database


## Configuration

Run the following command in your project folder

```bash
php artisan make:command CreateDatabaseCommand
```

Open the "mysql" file you just created and copy the contents of the file that is in the repository to it


## Use

The database access data must already be configured, if not, perform the configuration to continue

```bash
php artisan mysql:make-database "NOME_DO_BANCO"
```

After executing this command the database name was configured in your .env file and your database was created

Now just use your new database

Estas informações foram retiradas do [Stack Overflow](https://stackoverflow.com/questions/32191135/how-to-create-database-schema-table-in-laravel)


## License
[MIT](https://choosealicense.com/licenses/mit/)
