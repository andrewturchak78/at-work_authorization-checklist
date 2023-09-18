# Чек-лист 4-х Activities из Bored API

## Предварительные действия:
* Открыть Postman и создать новую коллекцию:

## Валидация Кеy:
1) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=999999, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
2) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=1000000, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с ключом 1000000.
3) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=1000001, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с ключом 1000001.
4) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=9999998, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с ключом 9999998.
5) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=9999999, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с ключом 9999999.
6) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=10000000, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
7) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?key=, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с рандомным ключом.

## Валидация type:
1) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=recreational, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом recreational.
2) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=education, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом education.
3) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=social, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом social.
4) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=diy, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом diy.
5) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=charity, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом charity.
6) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=cooking, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом cooking.
7) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=music, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом music.
8) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=relaxation, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом relaxation.
9) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=busywork, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с типом busywork.
10) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=dbuf124, нажать кнопку Send. **-->** ожидаем 400-й код ошибки или 200-й код, но с выводимым значением об ошибке.
11) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?type=, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с рандомным типом.

## Валидация participants:
1) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?participants=-1, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
2) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?participants=0, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с количеством участников 0.
3) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?participants=1, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с количеством участников 1.
4) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?participants=2, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с количеством участников 2.
5) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?participants=, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с рандомным количеством участников.

## Валидация price:
1) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?price=0, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с price 0.
2) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?price=0.5, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с price 0.5.
3) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?price=1, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с price 1.
4) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?price=-0.01, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
5) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?price=1.01, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
6) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?price=, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с рандомным price.
7) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?minprice=0&maxprice=0.1, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с price от 0 до 0.1.
8) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?minprice=-0.5&maxprice=-0.1, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
9) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?minprice=1.1&maxprice=2.1, нажать кнопку Send. **-->** ожидаем 400-ой ошибки или 200-го кода, но с выводимым сообщением об ошибке.
10) Создание нового get-запроса с url: http://www.boredapi.com/api/activity?minprice=&maxprice=, нажать кнопку Send. **-->** ожидаем 200-й код и вывод информации об activity с рандомными minprice и maxprice.
