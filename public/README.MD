# Тестовое задание FunBox

## Level I

>Q1
>
>Расскажите, чем, на ваш взгляд, отличается хорошая вертска от плохой с точки зрения:
-пользователя
с точки зрения пользователя основными моментами хорошей верстки являются дизайн, скорость работы сайта, адаптивность (возможность удобного использования сайта на любом устройстве), непергруженный (интуитивно понятный) интерфейс.

-менеджера проекта
с точки зрения менеджера проекта, хорошая верстка это та, которая удовлетворяет всем пунктам ТЗ и, процесс создания которой, укладывается в заданные сроки.

-дизайнера
с точки зрения дизайнера, хорошая верстка это та, которая максимально близко соответствует созданному макету и выполняет необходимые функции.

-верстальщика
с точки зрения верстальщика основными моментами хорошей верстки является читабельность и структурированность кода. Для легкого исправления или дополнения функционала (дизайна).

-клиентсокого и серверного программиста
для программистов хорошей будет та верстка, которая отвечает всем функциональным требованиям проекта. Легко читабельный и струтурированный код, интуитивно понятное название классов (функций или других компонентов).

>Q2
>Опишите основные особенности верстки крупных многостраничных сайтов,
дизайн которых может меняться в процессе реализации и поддержки.
>Расскажите о своем опыте верстки подобных сайтов: какие методологии, инструменты и технологии вы применяли на практике

При верстке крупных многостраничных сайтов, дизайн которых может меняться необходимо использовать компонентную струкуру проекта. Так будет проще и быстрее редактировать отдельные блоки без вреда для остальной структуры проекта. Код будет занимать меньше места, будет более читабельным. Разбиение проекта на отдельные компоненты способствует повышенной продуктивности. Необходимо грамотно передавать свойства от одного компонента другому, применяя валидацию. Писать обработчик ошибок.

Верстка учебных проектов на React JS (репозитории на моей странице GitHub), применение библиотеки PropTypes для валидации свойств.

>Q3
>Опишите основные особенности верстки сайтов, которые должны одинаково
хорошо отображаться как на любом современном компьютере, так и на
смартфонах и планшетах под управлением iOS и Android. Расскажите о своем
опыте верстки подобных сайтов: какие инструменты и технологии вы применяли,
как проверяли результат на различных устройствах, какие именно устройства
требовалось поддерживать. 

>ри верстки таких сайтов необходимо учитывать расположение элеметов (и удобство их использования пользователем) в зависимости от разрешения экрана. Не перегружать сайт лишней информацией, которая будет влиять на производительность.

Адаптивная верстка медиазапросы. Проверка выполняется с помощью инструментов разработчика в браузере (Chrome, Firefox), путем изменения размеров вьюпорта вручную или автоматически, выбрав необходимый гаджет.

>Q4
>Расскажите, какие инструменты помогают вам экономить время в процессе
написания, проверки и отладки кода. 

Линтеры, расширения для редактора ускоряющие набор текста (Emmet), дебаг провожу в Chrome Web Inspector.

>Q5
>Вам нужно понять, почему страница отображается некорректно в Safari на iOS и в
IE на Windows. Код писали не вы, доступа к исходникам у вас нет. Ваши действия?
Сталкивались ли вы с подобными проблемами на практике?

Необходимо получить описание бага, по нему можно будет сделать вывод (опираясь на особенности браузера) о некорректном отображении страницы.

>Q6
>Дизайнер отдал вам макет, в котором не показано, как должны выглядеть
интерактивные элементы при наведении мыши. Ваши действия?

Обратиться к дизайнеру и уточнить у него подробности макета. В случае отсутвия дизайнера самостоятельно принять решение по офромлению в соответвии с основным стилем проекта.

>Q7
>Какие ресурсы вы используете для развития в профессиональной сфере? Приведите
несколько конкретных примеров (сайты, блоги и так далее). 
>Какое направление развития вам более близко: JS-программирование, HTML/CSSверстка или и то, и другое? 
>Какие ещё области знаний, кроме тех, что непосредственно относятся к работе,
вам интересны?

Начал изучать веб-разработку с литературных источников ("Изучаем программирование на Python. Пол Бэрри."), далее в течение 9 месяцев проходил курс по специальности "Full-stack веб-разработчик на Python" на портале SkillFactory. Имею сертификат об успешном завершении курса. В данный момент изучаю React JS по видеоматериалам Владилена Минина (youtube).

Мне интересено как JS-программирование, так и верстка.

Помимо фронтов на JS интересуюсь также бэкендом на Python.

>Q8
>Расскажите нам о себе и предоставьте несколько ссылок на последние работы,
выполненные вами.

Ссылка на мое резюме на hh.ru : https://hh.ru/resume/7119503dff0642812d0039ed1f7976304e7536

Проекты:
https://github.com/6aldej/React-Table

https://github.com/6aldej/React-Weather

