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