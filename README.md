# Тестовое задание для front-end кандидатов. Мир данных ИТ.
Реализовать приложение для просмотра списка постов и добавление их в избранное.
## Задача
* Для данной задачи реализовать SPA-приложение.
* Реализовать в своем проекте три страницы: Общая страница, страница детального просмотра и страница для избранных постов.
* Для получения постов использовать запрос к серверу по url: https://jsonplaceholder.typicode.com/posts
* Для получения информация о конкретном посте использовать запрос к серверу по url: https://jsonplaceholder.typicode.com/posts/{id}
* Использовать один из трех front-end фреймворков: Angular, React или Vue.
* Нежелательно использование библиотек готовых компонентов(например, Ant Desing).

### Общая страница
 - На общей странице должен быть выведен список карточек постов.
 - В карточке должны быть выведены id и title поста, а также кнопка для добавления его в избранное.
 - По нажатию на саму карточку должен происходить переход на страницу детального просмотра.
 - Для полученных от сервера постов должна быть реализована пагинация по 10 элементов на страницу.
 - Реализовать возможность поиска статей по названию(поле title).
 - Кнопка перехода в избранные должна находиться на странице сверху.

### Детальная страница
На детальной странице в любом виде должна быть выведена вся информация о посте: id, title, body.

### Страница избранных постов
На этой странице должны находиться карточки постов, которые были добавлены в избранное. По нажатию на карточке тоже должен быть переход на детальный просмотр.

## Результаты
Ссылку на git c приложением или архив с исходниками скидывать на почту: a.lebedev@mir-dit.ru
