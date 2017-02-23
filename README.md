# Laravel Installer snap

This project creates a working snap of Laravel Installer

## Building

To build the snap:
  `snapcraft snap`
  
## Installing

To install your local snap:

  `snap install --classic --dangerous <snapfile>`
  
## Testing

Try making a new Laravel project:
  ```
 laravel new blog
 cd blog
 laravel.php artisan serve```
  
