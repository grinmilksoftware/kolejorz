# Installation

## 1. Clone repository
`git clone https://github.com/grinmilksoftware/kolejorz`

## 2. Move into directory you've created
`cd kolejorz`

## 3. Install dependencies
`docker run --rm -v $(pwd):/app composer install`
### You can change the ownership of directory to non root user
`sudo chown -R $USER:$USER kolejorz`

## 4. Create .env file based on .env.example
`cp .env.example .env`

## 5. Run containers
`./vendor/bin/sail up`

## 6. Generate key
`./vendor/bin/sail artisan key:generate`

## To add Vue.js
`npm install vue@next`
<br>
`npm install @vitejs/plugin-vue`
<br>
`npm install vue-router@next`
<br>
`npm i -D @vue-leaflet/vue-leaflet`

## TroubleShooting
in case of runnig this program on linuxbase system, you may encounter an error about Permission denied. Simple fix to that may be add  <br>
`WWWGROUP=1000` <br>
`WWWUSER=1000` <br>
to .env file
