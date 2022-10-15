## Live web chat application

![Screenshot](https://raw.githubusercontent.com/diamond95/LiveChat/master/2.png)

## Installing

- Create database
- Import

chat.sql

## Configure in 

database_connection.php

Move chat folder to your dolder web

/var/www/html/chat or c:\xampp\htdocs\chat

## Access via browser the folder chat

http://localhost/chat

Username - user1

Password - user1

## Create other password

If you are going to have limited users with some passwords use 

https://phppasswordhash.com/

to hash passwords and store into table login.

Otherwise if you are going to make **register** page as you wish use php5 function: 
```php
                     password_hash();
```

## Languages supported now

en - english

pt_BR - portuguese Brazilian

Configure in 

connection.php

## License

MIT

