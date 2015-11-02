# ProjectT 2015 v2 - Домашнее задание #1
## Задание 1.
### Выбрать программу для тестирования из списка:
Для тестирования выбрана программа Скайп

### Написать тест-план:
Скайп - программа, обеспечивающая текстовую, голосовую и видеосвязь, а также предлагает услуги для звонков на мобильные и стационарные телефоны.
Пользователем является каждый, кто зарегистрировался и скачал приложение.
Предположим, что оптимизировали блок программы, отвечающий за вывод в экране скайпа изображения из камеры.
Значит тестируем видеосвязь, видеоконференции.
Тестировать голосовые вызовы, передачу текстовых сообщений, прием-передачу файлов при этом тестировать не нужно, так как эти блоки совсем не связанны с выводом изображения от камеры.
Уровни.
Используем системные тесты, так как необходимо проверить работоспособность конечного продукта.
Используем интеграционные тесты, чтобы проверить правильное взаимодействие изменненых модулей программы, с теми, которые остались без изменения.
Используем модульные тесты, чтобы проверить правильную работоспособность измененных модулей.
Виды.
Функциональное тестирование, для проверки общей работоспособности.
Тестирование производительности, чтобы убедиться в том, что нет никаких задержек или лагов при подаче изображения.
Тестирование совместимости, чтобы убедиться в том, что в различных операционных системах все в порядке.
Протестировать на тех операционных системах, для которых поддерживается скайп.
Заканчиваем тестирование, когда проведем протестируем видеосвязь, видеоконференции, в различных операционных системах.

## Задание 2.
### Баг 1
Начальное условие: форма с сайтаhttp://testingchallenges.thetestingmap.org/index.php
Шаги выполнения: 
1) вместо имени оставлено пустое поле;
2) нажата кнопка submit.
Ожидаемый результат:
Будет уведомление о том, что поле не заполнено.
Реальный результат:
Tests done: 4 out of 18
Empty value
Minimum value
Other chars then alphabetic
Average value

### Баг 2
Начальное условие: форма с сайтаhttp://testingchallenges.thetestingmap.org/index.php
Шаги выполнения: 
1) введено имя 1Dima;
2) нажата кнопка submit.
Ожидаемый результат:
Будет уведомление о том, что имя не может начинаться с цифры.
Реальный результат:
Tests done: 2 out of 18
Other chars then alphabetic
Average value

### Баг 3
Начальное условие: форма с сайтаhttp://testingchallenges.thetestingmap.org/index.php
Шаги выполнения: 
1) введено имя Diма;
2) нажата кнопка submit.
Ожидаемый результат:
Будет уведомление о том, что имя не может состоять из символов различных кодировок.
Реальный результат:
Tests done: 3 out of 18
Non ASCII
Other chars then alphabetic
Average value

## Задание 3 (опционально, будет плюсом).
Предположим, я тестировщик в одной из команд 2ГИС, например, в команде ответственной за корректную работу приложения 2ГИС на устройствах с операционной системой Windows Phone.
Значит на мне лежит ответственность за то, чтобы конечный продукт, который выйдет на устройство Windows Phone не имел багов.
Для этого я должен постоянно взаимодействовать с разработчиками, чтобы в случае изменения какого-то отдельного модуля, его можно было сразу протестировать, а также проверить взаимоействия этого модуля с другими частями программы.
Кроме того, необходимо иметь набор базовых тестов, который будет выполняться каждый раз при выходе нового релиза программы, для того чтобы убедиться в том, что новый релиз не хуже предшествующего.

## Задание 4 (опционально, будет плюсом).
Ошибка может произоити в технической подсистеме. Это значит, что какой-то набор входных данных не предусмотрен в программе и происходит сбой. Причиной может являться как то, что разработчики и тестировщики не предвидели подобный вариант входных данных, так и то, что техническое оборудование эксплуатируется не должным образом. 
Однако, ошибка может произойти из-за того, что есть злоумышленник, который умышленно приводит систему в состояние, в котором она функционирует не должным образом. 

