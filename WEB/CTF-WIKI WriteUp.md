# CTF-WIKI

Мы сделали вики, чтобы вам было проще вникнуть в CTF.

# Solve

1.Переходим на сайт. После долгого(нет) поиска, находим один единственный параметр file.

![step1](https://i.imgur.com/He57ILc.png)

2.После неких манипуляций понимаем что это названия файлов. пробуем считывать другие файлы(Получается). В /etc/passwd видим строку "Are you sure that flag in a file?" (долго курим и плачем).

![step2](https://i.imgur.com/fAT63Zh.png)

3.Не ведемся на повадки и пробуем все возможные варианты системных файлов (https://thesecurityvault.com/path-traversal-lfi-can-be-worst-than-you-think/)

![step3](https://i.imgur.com/5CHMslG.png)

4.После бесонной ночи вы находите env файл

![step4](https://i.imgur.com/BDbpzjc.png)

5.Вы безупречны!
