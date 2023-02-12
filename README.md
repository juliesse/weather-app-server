# weather-app-server

Installation Steps:
create .env file based on .env.example

Run the following commands:
composer update
php artisan key:generate
php artisan jwt:secret
php artisan cache:clear
php artisan config:clear
php artisan serve

Clone the client side of the app in this link: https://github.com/juliesse/weather-app-client

About:

This app is built using VueJS and Laravel.

Geoapify is used to retrieve places details like city and country code.

OpenWeather API is utilized for fetching the current weather and forecast for selected city.

Tokyo is the default city. Its weather details will be loaded once the app is visited.

City selection contains Tokyo, Yokohama, Kyoto, Osaka, Sapporo, and Nagoya. The app is not only limited to the cities mentioned.
User may type any city they want to check.

It is responsive on all devices. The set of codes also follows coding standards and best practices. Proper naming of variables,
classes, and methods has been applied for easier understanding and debugging so that there will be no need for comments. All the 
logic are in the controller. KISS, YAGNI, and SOLID are also implemented.