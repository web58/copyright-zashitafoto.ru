# Лендинг по защите авторских прав фотографий «Авторский знак»

## Информация по сборке
> Версия / Version 2.0.3 <br>
> Автор / Author [putn1k](https://github.com/putn1k/) <br>
> Используется / Use Gulp 4 <br>
> Используется / Use Node 16.x <br>
> Используется / Use npm 8.x <br>

[Как работать со сборщиком](Workflow.md)

## Важно!

Так как файл `private_settings.php` подключаемый к файлам настройки отправки находится в .gitignore, то его нужно будет создать заново. Файл имеет примерную структуру:<br>
```php

$tlgbot_token = 'токен телеграм бота';
$chat_id = 'идентификатор чата';

$admin_email  = 'email администратора';
```
Эти, а также все другие необходимые переменные, которые не должны публиковаться должны быть занесены в этот файл.