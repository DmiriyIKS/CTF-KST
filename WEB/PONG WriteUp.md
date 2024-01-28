# Pong

Поиграем?

# Solve

1.Переходим на сайт и видим страничку умеющую пинговать. Зная что ping системная утилита предполагаем что это Command Injection.

![step1](https://i.imgur.com/Jjfjaim.png)

2.Спотыкаясь через несколько фильтров приходим к иньекции.

```
ip=127.0.0.1%0aprintenv
```

![step2](https://i.imgur.com/b2nTAOO.png)
