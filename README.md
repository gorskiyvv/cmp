# Розпізнавання зображень
Даемй проєкт реалізує систему розпізнавання об'єктів на зображеннях за допомогою глибокого навчання. Модель навчена на датасеті CIFAR-10 та визначає категорії об'єктів, таких як літаки, автомобілі, птахи, коти, олені, собаки, жаби, коні, кораблі та вантажівки.
## Зміст
- [Опис проєкту](#Опис-проєкту)
- [Використані бібліотеки та технології](#Використані-бібліотеки-та-технології)
- [Інструкція з користування](#Інструкція-з-користування)
- [Рекомендації](#Рекомендації)
- [Встановлення необхідних компонентів](#Встановлення-необхідних-компонентів)
- [Команда розробників проєкту](#Команда-розробників-проєкту)

## Опис проєкту
Цей проєкт включає в себе навчання моделі за допомогою ноутбука model training.ipynb, веб-додаток app.py для розпізнавання об'єктів на зображеннях, а також збережену модель model.h5. Результати передбачень та зображення можна переглянути на веб-сторінках, визначених в шаблонах archive.html та index.html.

## Використані бібліотеки та технології

-Мова програмування: Python
-Веб-фреймворк: Flask
-Бібліотеки машинного навчання: Keras, TensorFlow
-Інші бібліотеки: Pillow (PIL), NumPy, base64


## Інструкція з користування

1. Навчання моделі: Використовуйте ноутбук model training.ipynb для навчання моделі на датасеті CIFAR-10.
2. Запуск веб-додатку: Використовуйте файл app.py для запуску веб-додатка. Додаток буде доступний за адресою http://localhost:5500/.
3. Розпізнавання зображень: Завантажте зображення на головній сторінці, натискайте "RECOGNIZE IMAGE" та переглядайте результати.
4. Перегляд архіву результатів: На сторінці "Аrchive" можна переглянути раніше зроблені передбачення.

### Рекомендації
Якщо ви бажаєте внести зміни або розширити функціонал, дотримуйтеся наступних кроків:

-Завантажте необхідні бібліотеки, використовуючи requirements.txt.
-Редагуйте або додавайте новий код в app.py або HTML-файли.
-Переконайтеся, що всі зміни тестуються локально перед внесенням коміту.

### Встановлення необхідних компонентів
Для встановлення необхідних компонентів виконайте команду
```sh
$ pip install -r requirements.txt
```

## Команда розробників проєкту
Оставьте пользователям контакты и инструкции, как связаться с командой разработки.

- [Подоляк Б. Ю.](tg://resolve?domain=Hentai_Sommelier) — Тімлід
- [Питулько Д. В.](tg://resolve?domain=timerfimer) — Scrum мастер
- [Паєвська Д. І.](tg://resolve?domain=dipvsk)
- [Святенко Д. В.](tg://resolve?domain=W1nnd)
- [Горський В. В.](tg://resolve?domain=vv0311)