# Домашнее задание к лекции 2.1 «Tests»

### Задача №1 unit-tests
Из курса «Python: программирование на каждый день и сверхбыстрое прототипирование» протестирована программа по работе с бухгалтерией [Лекции 2.1](https://github.com/netology-code/py-homework-basic/tree/master/2.1.functions).

* Протестированы основные функции по получению информации о документах, добавлении и удалении элементов из словаря.
* Использован fixture для загрузки данных в тестовый класс.

### Задача №2 Автотест API Яндекса
Проверена актуальность API Яндекс.Переводчик'а для потенциального сервиса переводов.
Используя библиотеку request написан unit-test на верный ответ и возможные отрицательные тесты на ответы с ошибкой.

Пример положительных тестов:
* Код ответа соответствует 200
* результат перевода правильный - "привет"

### Задача №3. Дополнительная (не обязательная)
Применив selenium написан unit-test для авторизации на Яндексе по url: https://passport.yandex.ru/auth/
