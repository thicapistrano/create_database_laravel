# Command for database create in laravel 


## Configuration

Run the following command in your project folder

```bash
php artisan make:command CreateDatabaseCommand
```

Open the "mysql" file you just created and copy the contents of the file that is in the repository to it


## Use

The database access data must already be configured, if not, perform the configuration to continue

```bash
php artisan mysql:make-database "NAME_DATABASE"
```

After executing this command the database name was configured in your .env file and your database was created

Now just use your new database


## License
[MIT](https://choosealicense.com/licenses/mit/)
