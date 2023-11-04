# Guest_room_booking
``` git  clone https://github.com/javedbaloch4/Laravel-Booking.git ```

``` Open .env file to configure your database name, host, and password ``` 
 Open `.env` file to configure your `database` and it's `name`, `host`, and `password` 

``` composer install ```

``` php artisan migrate ```
``` cp .env.example .env ``` / ``` copy .env.example .env ```

``` php artisan db:seed ```
``` php artisan key:generate ```

``` php artisan migrate --seed ```

``` php artisan serve ```

** localhost:8000/ **
`localhost:8000`

House owners:
- Can register for an account with an email address and a mobile number
- Create / edit / delete rooms and their details, set the minimum, maximum booking period.
Set a rent amount for each day
- Upload photos
Customers:
- Can register for an account with an email address and a mobile number
- They can browse all rooms available for booking
- View details of each room, and their photos
- See an “Availability calendar
- Choose the dates and book
