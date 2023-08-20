Just another template. please add appropriate env

Run docker-compose
------------------

```bash
docker-compose up -d --build
```

Create laravel project
----------------------

this [installation] will init your [`src` folder]. (You may need to create an empty directory)

```bash
docker-compose run --rm composer create-project --prefer-dist laravel/laravel .
```

[installation]: https://laravel.com/docs/10.x#your-first-laravel-project
[`src` folder]: ./src