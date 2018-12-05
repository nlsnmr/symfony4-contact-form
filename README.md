# Symfony Contact Form

### A basic Contact form App With Symfony 4

This contact form can send emails using Gmail, SMTP and Cloud.  
I will recommend give a look on the Symfony website in the [documentation](https://symfony.com/doc/current/email.html) that describes how to send an email using Gmail, SMTP and Cloud services

__Symfony version__: 4  
__Symfony skeleton__: website-skeleton  
__Template engine__: Twig  
__Frontend framework__: Bootstrap 4 (Bootstrap CDN)

![Image](https://monosnap.com/image/n9plfLkFgJH9eJVUI742caY3dKO5Rg.png "Image")

## Installation

``` bash
# Install dependencies
composer install

# Edit the .env file (or .env.local) to update MAILER_URL option, ex:
MAILER_URL=smtp://<address>:<port>?encryption=tls&auth_mode=login&username=<your_username>&password=<your_password>

# Now let's fire up the web server and take a look on this contact form:
php bin/console server:start
```
