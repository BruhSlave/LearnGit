#git #github 
-  - -
## Установка имени и электронной почты
#### Выполните
```
git config --global user.name "Your Name"
git config --global user.email "your_email@whatever.com"
```

## Имя ветки по умолчанию
Мы будем использовать `main` в качестве имени ветки по умолчанию. Чтобы установить его, выполните следующую команду:
#### Выполните
```
git config --global init.defaultBranch main
```

## Корректная обработка окончаний строк
Для пользователей Unix/Mac:
#### Выполните
```
git config --global core.autocrlf input
git config --global core.safecrlf warn
```

Для пользователей Windows:
#### Выполните
```
git config --global core.autocrlf true
git config --global core.safecrlf warn
```