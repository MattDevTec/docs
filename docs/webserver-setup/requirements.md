# Requirements

## Webserver Requirements
Please ensure that the minimum requirements are met to ensure LinkStack functions as expected.

- Apache Web Server with .htaccess support
- Apache Module mod_rewrite
- At least PHP 8.1 or above
- Read and write access to files in the root directory, as well as all LinkStack Directories
- Access over HTTPS and with a valid SSL certificate

## Required PHP Modules

Please ensure that all the PHP modules listed below are installed and enabled on your webserver, without these LinkStack will not function.

- BCMath PHP Extension
- Ctype PHP Extension
- cURL PHP Extension
- DOM PHP Extension
- Fileinfo PHP Extension
- JSON PHP Extension
- Mbstring PHP Extension
- OpenSSL PHP Extension
- PCRE PHP Extension
- PDO PHP Extension
- Tokenizer PHP Extension
- XML PHP Extension

Depending on your database type:

- SQLite PHP Extension (default option, no database configuration is required)
- MySQL PHP Extension 

Please note that this documentation does not apply to Docker hosted instances, and will not be correct. If you are using Docker, please see the documentation [here]