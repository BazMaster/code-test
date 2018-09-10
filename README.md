# Тестовое задание Freelancehunt

## 🏆 Quest 1 
Вы присоединились к небольшому стартапу из 8 человек, который предоставляет путешественникам возможность отмечаться из разных стран 
и строить карту своих путешествий, а также следить, где побывали из друзья.  
Менеджер по продукту очень рад, что в команде наконец появился разрабочик, и передал вам файл [input.json](input.json), 
в котором он вручную отслеживал пользователей и очень просил все автоматизировать. Например, он знает, с какого IP 
отмечались пользователи, но не знает, какая это страна.
Вы уточнили у Евгения значения колонок в файле: 

| Колонка            | Описание                                                                                       |
|--------------------|------------------------------------------------------------------------------------------------|
|  name              | Имя путешественника. Имя уникально: если Ольга встречается два раза, это один человек, но Ольга и Olga — разные люди |
|  checkin_date | Дата чекина из определенной страны                                                                               |
|  ip                | IP адрес, с которого путешественник сделал чекин. По нему определяется страна, в которой путешественник побывал.                                                  |
|  rating            | Рейтинг, полученный за чекин в данной стране.                                                                        | 
|  home_country      | Страна проживания путешественника. Используется только для отображения.                                                                                         |
|  is_active         | Активен путешественник или нет. Используется для фильтрации.                 |

### Какие перед вам стоят задачи? 🧠🤔

1. Создать [single page application](https://en.wikipedia.org/wiki/Single-page_application), выводящую все записи из базы в табличном виде и позволяющие фильтровать по стране, в которой и флагу активности.
2. Для всех отфильтрованных записей над таблицей нужно отображать средний рейтинг для текущей выборки и имя пользователя, который набрал максимальный общий рейтинг (помните, что для одного пользователя записей может быть несколько). 
3. В таблице зеленым цветом подсвечивать запись (или записи) путешественников с максимальным рейтингом для данной страны. 

## Условия 📙

1. Язык реализации на бекенде: на ваше усмотрение, можно просто отдавать полный JSON и обрабатывать его на клиенте.
3. Стек на фронтенде: Vue.js или React.
4. Получение геоданных по IP: на ваше усмотрение (например, [IPInfo](https://ipinfo.io/developers#jsonp-cors-requests))
5. Настроенная сборка под production: на ваше усмотрение, например Webpack.
6. Расширение CSS: плюс за использование less или sass 🏅
7. Тесты, без них никак 🏅
8. Код вместе с инструкцией по запуску выложить на Github.


# Что дальше?
Ответы на вопросы отправляйте на join@freelancehunt.com — мы их оценим и сможем обсудить на Skype-интервью. Желаем удачи! 🤞
