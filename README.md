# En: Skillbox_JavaScript-module-17_modules_task-1
# Ru: Skillbox_JavaScript-модуль-17_модули_задание-1

#### Please give this project a star ⭐ if you found it interesting
#### Пожалуйста, поставьте звезду ⭐ если этот проект Вас заинтересовал

### En:
#### Task 1
What You Need to Do
Build a small web application for managing a warehouse inventory list, consisting of two dynamically loaded pages:
“Warehouse” and “Add Entry”.
Navigation between pages should include a preloader to indicate loading status.

Data Handling
All item records should be stored as an array in localStorage.
When the page reloads, the data should be loaded from localStorage.

On the “Warehouse” Page, Display:
- A page title
- A “Add Entry” button that navigates to the entry form page
- A table listing all items, with the ability to sort each column in ascending order when clicking the column header
- Each item should have a “Delete” button to remove it from the list

On the “Add Entry” Page, Display:
- A page title
- A form with an “Add” button and the following fields:
- Name
- Shelf
- Weight
- Storage Time

Make sure to implement input validation for each text field.
After successfully adding an entry, the app should automatically redirect to the list page.

Implementation Notes
- Pixel-perfect layout is not required, but the overall style and appearance should match the provided design
- JavaScript code must be modularized — separate modules for pages and components
- Create a dedicated module for working with localStorage

Optional Task (Bonus)
For extra practice, you may add:
- A search feature for filtering entries
- An edit feature on a separate page to update existing entries
Task Completion Criteria
- No errors in the console
- The web application works correctly and meets the task requirements
- JavaScript modules are used
- Pages are loaded dynamically
- DOM elements are styled according to the provided layout


____________________________________________________________________________________________________

### Ru:
#### Задача 1
Что нужно сделать
Реализуйте небольшое веб-приложение для списка вещей на складе, которое должно состоять из двух динамически загружающихся страниц: «Склад» и «Добавить запись». Навигация между страницами должна сопровождаться показом прелоадера для отображения статуса загрузки.

Данные о записях должны храниться в виде массива в локальном хранилище localStorage и при перезагрузке страницы должны загружаться оттуда же.

На странице списка необходимо показать:

Заголовок страницы.
Кнопку «Добавить запись», при клике на которой выполняется переход на страницу добавления записи.
Таблицу со списком вещей и возможностью сортировки записей по возрастанию в каждой колонке при клике на названии колонки. У каждой записи должна быть кнопка удаления из списка.
На странице добавления записи необходимо показать:

Заголовок страницы.
Форму с кнопкой добавления и полями:
«Название»,
«Полка»,
«Вес»,
«Время хранения».
Не забудьте добавить валидацию ввода данных для каждого текстового поля. После успешного добавления записи должен быть выполнен автоматический переход на страницу со списком.

Пример реализации приложения:
В этом задании не требуется вёрстка pixel perfect, но общая стилистика и вид должны быть сохранены.

Важно! JavaScript-код должен быть разделён на модули с учётом страниц и компонентов. Для функций работы с локальным хранилищем также создайте отдельный модуль.

Дополнительное задание (необязательное)
Для получения дополнительной практики можете добавить возможность поиска записей и редактирования записи на отдельной странице.

Критерии выполнения задания
В консоли нет ошибок.
Код веб-приложения работает корректно, в соответствии с заданием.
В работе используются модули.
Страницы загружаются динамически.
DOM-элементы стилизованы в соответствии с предложенным макетом.


## En: Technologies Used
## Ru: Используемые технологии

- HTML5
- CSS
- JavaScript

## En: License
This project is for educational purposes only. Do not copy or redistribute without permission.

## Ru: Лицензия
Этот проект предназначен исключительно для образовательных целей. Не копируйте и не распространяйте без разрешения.

## En: Demonstration
## Ru: Демонстрация
![1_1-1](https://github.com/user-attachments/assets/3af6decd-f21f-4934-bdd7-7be01687ba3b)
![1_1-2](https://github.com/user-attachments/assets/f6588750-2817-43a5-8e71-30b1ad2188bd)
![1_1-3](https://github.com/user-attachments/assets/288e8a6c-c8e1-4aec-843d-d8104aa12e97)































