# Criar Banco de Dados no Laravel


## Configuração

Execute o seguinte comando na pasta do seu projeto

```bash
php artisan make:command CreateDatabaseCommand
```

Abra o arquivo "mysql" que você acabou de criar e copie o conteúdo do arquivo que está no repositório para ele


## Utilizar

Os dados de acesso ao banco de dados já devem estar configurados, caso não esteja, realize a configuração para continuar

```bash
php artisan mysql:make-database "NOME_DO_BANCO"
```

Após executar este comando o nome banco de dado foi configurado no seu arquivo .env e seu banco de dados foi criado

Agora é só utilizar seu novo banco de dados

Estas informações foram retiradas do [Stack Overflow](https://stackoverflow.com/questions/32191135/how-to-create-database-schema-table-in-laravel)


## License
[MIT](https://choosealicense.com/licenses/mit/)
