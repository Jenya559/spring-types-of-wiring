# spring-types-of-wiring

1. Склонировать заготовку с репозитория
2. Реализовать цепочку зависимостей, чтобы продолжить фразу "На свете есть океан , на океане остров , на острове дерево , на дереве заяц , в зайце утка"

Алгоритм работы программы:
- в методе main из application context достаем bean по имени класса KoscheiTheDeathless.class
- у бина вызываем метод getRulesByDeth()

Пример вывода в консоль:
"На свете есть океан , на океане остров , на острове дерево , на дереве заяц , в зайце утка , в утке яйцо , в яйце иголка , смерть Кощея на игле :("

Проверить работоспособность логики можно с помощью запуска автотестов.