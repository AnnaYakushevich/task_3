## Первоначальная настройка Git

1. Имя пользователя

Используя команду `git config`, укажите ваше имя пользователя и e-mail. Эта информация будет содержаться в каждом вашем коммите и ее нельзя будет изменить. Пример:

~~~bash=
git config --global user.name "Anna"
git config --global user.email anna@example.com
~~~

2. Проверка настроек

Если вы хотите проверить используемую конфигурацию, можете использовать команду ``git config --list``, чтобы показать все настройки, которые Git найдёт. Например:

```bash=
git config --list
user.name=Anna
user.email=anna@example.com
color.status=auto
color.branch=auto
color.interactive=auto
color.diff=auto
```

