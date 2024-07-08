### Important things learned

`sail artisan install:api`

It will active the API for laravel

`sail artisan make:resource CategoriaCollection`

It will create a collection for the resource that will be returned

`sail artisan make:resource CategoriaResource`

It will create a resource that handles how and what data will be returned

`sail artisan migrate:refresh --seed`

It will refresh the entire database and seed it with the data

`sail artisan make:model Producto --resource --api --migration`

It will create a model, a resource controller (normal controller but with default methods used for an api) and a migration

`sail artisan make:request RegistroRequest`

It will create a request that will handle the validation of the data for a register request

`sail artisan config:publish cors`

It will publish the cors configuration file to the config folder

- We need to use HasApiTokens in the User model to be able to use the Passport package and be able to return users