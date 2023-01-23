This repo is to demonstrate the issue discussed at https://github.com/JonasKruckenberg/imagetools/issues/396

Instructions to run the project

1. Rename `.env.example` to `.env`
2. Run `composer install`
3. Run `npm install`
4. Run `php artisan key:generate`
5. Run `php artisan serve` in a terminal and keep it open
6. In another terminal run `npm run dev` and also keep it open
7. Visit the url given by the `serve` command (step 5)
8. You can see the image fails to load since it's going through `vite-imagetools` plugin via the `?webp`
9. The file you want to edit/play with is `resources/views/pages/welcome.vue`


Obviously you also need to have `node`, `npm`, `composer` and `php` installed on your machine.