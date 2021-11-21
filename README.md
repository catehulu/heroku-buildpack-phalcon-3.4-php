# Heroku buildpack: PHP 7.3 and Phalcon 3.4

![phalcon](https://assets.phalcon.io/phalcon/images/svg/phalcon-logo-transparent-black.svg)

A heroku PHP buildpack for Phalcon 3.4

Feel free to change or update

## Usage

``` 
heroku create phalcon-heroku-test // change the project name
heroku config:set BUILDPACK_URL=https://github.com/catehulu/heroku-buildpack-phalcon-3.4-php 
git push heroku main
```

Tested on 21-11-2021 here https://phalcon-heroku-test.herokuapp.com/test.php  
Using this repository https://github.com/catehulu/phalcon-heroku-test  

resource :  
https://www.sitepoint.com/install-custom-php-extensions-heroku/  
https://devcenter.heroku.com/articles/php-support  
