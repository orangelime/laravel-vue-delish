# laravel-vue-delish

## Live Demo

https://vue-delish.herokuapp.com/#/index

sign in demo:

email address:1234@email.com
password:1234

## How to use

- Clone the repository with __git clone__

__Back-end__

- Go to the sub-folder `cd laravel-api-Delish`
- Copy __.env.example__ file to __.env__ and edit database credentials there
- Run __composer install__
- Run __php artisan key:generate__
- Run __php artisan migrate --seed__ (it has some seeded data for your testing)
- Run __php artisan passport:install__


__Front-end__

- Go to the sub-folder `cd vue-Delish`
- Run __touch .env.local__
- Add correct value of your domain for backend URL in this variable: `VUE_APP_API_URL=[your_domain]`
- Run __npm install__ 
- Run __npm run start__ 
- That's it: launch the URL that appears in the terminal - could be `http://localhost:3000`
- front-end commit's detail https://github.com/orangelime/Delish

