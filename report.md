# Отчет о тестировании валидации номеров банковских карт

## Краткое описание

3 марта 2012 было проведено тестирование функциональности валидации номеров банковских карт
На тестирование затрачено: 1 час

## Описание процесса тестирования

1. Открыть код в программе IntelliJ IDEA

![](https://downloader.disk.yandex.ru/preview/e8b58e9b3ad0fff0d76afd23a4d291867a5161eec95bbfc6669745a7b7b35ec4/603fb6fd/R_sSwvAs4I6GpB9gb_GUcjb9PbI4PJMu1urL-A4dR2DjLqWOSwG6Z4974yLhn7E0TKjkgsbYe_7IYg4J5qQQNQ%3D%3D?uid=0&filename=code.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&tknv=v2&size=2048x2048)

2. В значении String number, 4 строка, ввести номер карты "371647737670678"

2. Нажать сочетание клавиш Ctrl+Shift+F10

2. Обратить внимание на выводимый результат кода

* ОР
В результате выполнения кода появляется надпись: Result is ОК

* ФР
В результате выполнения кода появляется надпись: Result is FAIL

![](https://downloader.disk.yandex.ru/preview/292cd79d78576b7dbfdf9b7a79456b7e583bbc4681a87ace04e2144bd3f9f971/603fb8b7/rJM704MtQ5B-_eMUFc5s2ucW9qCoudCqSW3We4we7QK_SPbV3S-3AjzBCK0iXQxuKDRkUjgp4A6WAhcDMcTklw%3D%3D?uid=0&filename=result.png&disposition=inline&hash=&limit=0&content_type=image%2Fpng&owner_uid=0&tknv=v2&size=2048x2048)


## Тестирование проводилось в следующем окружении
Версия и разрядность ОС: Windows 10 Pro, 64 bit
Версия Java: Version 8 Java (build 1.8.0_281-b09)


