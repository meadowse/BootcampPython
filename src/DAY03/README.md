# DAY 03 – ООП в Python
## Классы, наследование, атрибуты классов и объектов
В рамках этого дня вы изучите, как устроена объектная модель в Python.

### Преамбула

Объектно-ориентированное программирование (ООП) - это базовое понятие теории программирование и основа большинства языков программирования, в т.ч. и Python. Концепция ООП подразумевает, что в программе есть некоторые сущности, именуемые объектами, которые взаимодействуют друг с другом. Объекты могут быть отнесены к одному или нескольким классам (несколько классов - это вариант множественного наследования, которое реализовано не во всех ООП языках, но в питоне есть). Таким образом, получается, что программист описывает классы, где указаны значения и функции (методы), которыми обладает каждый объект этого класса, а дальше создаются объекты этих классов и описывается их взаимодействие. Примером класса может быть пользователь сервиса. Мы описываем то, что у пользователя есть логин, имя, дата регистрации, функция обновления статуса, функция отправки сообщения и т.д., а у конкретных объектов-пользователей хранятся конкретные значения описанных полей, которые используются в общей описанной логике функций класса. Кстати говоря, сообщение тоже может быть классом, и тогда объекты этого класса будут хранить информацию о том, кто является отправителем и получателем, какой в сообщении текст и т.д. То, как описываются классы в питоне, а также особенности хранения значений и функций в объектах и классах, мы рассмотрим в сегодняшнем уроке.

### Цели

Наша цель - освоить ООП в питоне.

### Задание

В этом дне вас ждут 2 задачи, в которых нужно будет описать классы, которые можно проверить автоматически в Яндекс.Контесте по ссылке https://contest.yandex.ru/contest/40435/enter/

Что нужно сделать:
1. Напишите скрипт, решающий задачу, описанную по адресу https://contest.yandex.ru/contest/40435/problems/14/.
2. Напишите скрипт, решающий задачу, описанную по адресу https://contest.yandex.ru/contest/40435/problems/15/.

Все решения должны проходить соответствующие тесты из Яндекс.Контеста. Соответствие задач из контеста задачам из задания приведено в блокнотах с конспектами.

### Сдача работы и проверка

Вам нужно загрузить в GIT в папку `src` свой Jupyter Notebook, в котором заполнены ячейки, предусмотренные для решения заданий.
