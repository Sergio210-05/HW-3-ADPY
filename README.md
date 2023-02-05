# Домашнее задание к лекции 6.«Web-scrapping»

## Функция vacancies
Основная функция vacancies имеет следующие аргументы:

__url__ > str - ссылка на первую страницу поискового запроса

__*key_words__ - перечень ключевых слов для фильтрации вакансий, в данном случае "django" и "flask"

__num_pages__ > int - необязательный агрумент. Колличество страниц, по которым производить поиск . Если не задан - поиск ведётся по всем страницам (общее кол-во страниц определяется функцией pages_quantity(url))

__usd__ > bool - необязательный аргумент. По умолчанию False. Если установлен True - выдает вакансии с зарплатой в доллларах