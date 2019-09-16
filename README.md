# Тестовое задание. Подбор новостей.

## Описание
Требуется реализовать приложения загрузки случайной новости с помощью Reddit API.

## Задача
Всего есть 4 темы (subreddits):
- frontend
- reactjs
- vuejs
- angular

Для каждой из них есть бегущая строка с элементом содержащим название темы.
При клике на элемент, он останавливается и подсвечивается.
После этого происходит запрос на сервер статей по данной теме.
Затем показывается ссылка на одну случайную статью.

### Пример (gif)

![alt gif_ex](https://raw.githubusercontent.com/dsvgit/redux-test/master/gif-demo-1.gif)

### Пример (image)

![alt image_ex](https://raw.githubusercontent.com/dsvgit/redux-test/master/jpg-demo-1.jpg)

## Требования
1. Все компоненты не должны иметь локального стейта.
2. Состояние приложения полностью должно контролироваться redux стором.
3. Все сайд эффекты должны быть написаны на redux-saga (например: запросы на сервер, интервалы, таймауты и все прочее что вам может понадобится)
4. Проект должен быть развернут в сети интернет, любым удобным способом (можно сделать в https://codesandbox.io)

## Дополнительно
- API можно посмотреть тут - https://codesandbox.io/s/72j28q2k50
- Способ анимации на ваш выбор

## Оценка
Оценивается
- проектирование структуры стейта
- понимание стека react/redux/saga
- качество кода
- время выполненеия (не в ущерб качеству)
