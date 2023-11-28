# CROC-IT-School

### Оглавление
1. [Описание проблемной ситуации](#описание-проблемной-ситуации)
2. [Основные стейкхолдеры проблемной ситуации](#основные-стейкхолдеры-проблемной-ситуации)
3. [Решение](#решение)
4. [Основные стейкхолдеры решения](#основные-стейкхолдеры-решения)
5. [Функциональные требования к системе](#функциональные-требования-к-системе)
6. [Экраны системы/Пользовательские интерфейсы](#экраны-системыпользовательские-интерфейсы)
7. [Функциональные компоненты решения](#функциональные-компоненты-решения)
8. [Технологии для создания компонентов решения](#технологии-для-создания-компонентов-решения)
9. [Ресурсы](#ресурсы)
10. [Команда](#команда)
11. [Риски](#риски)
12. [MVP](#mvp)

[Хронология курса "Школа ИТ решений"](CROC_Chronology.md)

# Паспорт проекта

### Описание проблемной ситуации
> Наш пользователь - Александр Жигулев. Он
хочет отслеживать работу учеников на дистанционных уроках.
Но не может, потому что ему мешает отсутствиее постоянного контакта с учениками, отсутствие возможности видеть одновременно всех учеников, а так же отстутствие возможности вмешиватся в самостоятельную работу учеников.
Существующие решения, такие как: Zoom, Google meet. Не предоставляют инструментов, способных помочь в решении вышеперечисленных трудностей.  

### Основные стейкхолдеры проблемной ситуации

<details><summary><h3 style="display:inline">Преподаватель</h3></summary>
    
</details>
<details><summary><h3 style="display:inline">Ученик</h3></summary>

</details>

### Решение
Для учащихся и преподавателей, которым нужно эффективное и удобное дистанционное обучение, наше веб-приложение будет предоставлять возможность вести свои персональные доски, на которых преподаватель может вносить правки и оставлять комментарии, тем самым помогая ученикам. В отличие от Zoom и Google Class - приложений, которыми пользуется больинство людей на дистанционном обучении, наш продукт реализует возможности очного обучения в дистанционном формате, а именно возможность во время занятий отслеживать, что пишут ученики, делать пометки в их тетрадях (персональных досках).

### Основные стейкхолдеры решения

<details><summary><h3 style="display:inline">Пользователь</h3></summary>

- <details><summary><h3 style="display:inline">Учитель</h3></summary>
    <b>Кто таков:</b>
    
    Любой человек, который хочет проводить занятия с иллюстрированием различной информации

    <b>Чего хочет:</b>

    Возможность 

    <b>Что мы от него хотим:</b>

    <b>Наше ценностное предложение для него</b>

    </details>

- <details><summary><h3 style="display:inline">Ученик</h3></summary>
    <b>Кто таков:</b>

    <b>Чего хочет:</b>

    <b>Что мы от него хотим:</b>

    <b>Наше ценностное предложение для него</b>

    </details>


</details>

<details><summary><h3 style="display:inline">Заказчик</h3></summary>

- <details><summary><h3 style="display:inline">Образовательные организации</h3></summary>
    <b>Кто таков:</b>

    <b>Чего хочет:</b>

    <b>Что мы от него хотим:</b>

    <b>Наше ценностное предложение для него</b>

    </details>

</details>

<details><summary><h3 style="display:inline">Партнеры</h3></summary>

- <details><summary><h3 style="display:inline">Zoom</h3></summary>
    <b>Кто таков:</b>

    <b>Чего хочет:</b>

    <b>Что мы от него хотим:</b>

    <b>Наше ценностное предложение для него</b>

    </details>

</details>

<details><summary><h3 style="display:inline">Конкуренты</h3></summary>

</details>

<details><summary><h3 style="display:inline">Регулятор</h3></summary>

- <details><summary><h3 style="display:inline">Роскомнадзор</h3></summary>
    <b>Кто таков:</b>

    <b>Чего хочет:</b>

    <b>Что мы от него хотим:</b>

    <b>Наше ценностное предложение для него</b>

    </details>

</details>

<details><summary><h3 style="display:inline">Команда</h3></summary>

</details>

<details><summary><h3 style="display:inline">Место внедрения и его держатель</h3></summary>

</details>

<details><summary><h3 style="display:inline">Источники ресурсов</h3></summary>

</details>


### Функциональные требования к системе
#### Основной интерфейс 
- Регистрация/вход для учителей и учеников
- Создание и редактирование групп учеников
- Запуск/проведение занятий с группами учеников
- Возможность быстро подключаться к занятиям (возможность подключаться без регистраци)
#### Интерфейс занятия
- Редактирование персональной доски для всех участников занятия
- Просмотр и редактирование досок учеников для учителя  
- Просмотр доски учителя для учеников
- Завершение
#### Инструменты для редактировния
- Рука
- Ручка
- Ластик
- Формы
- Таблицы
- Действие вперед/назад
- Текст
- Комментарии
### Экраны системы/Пользовательские интерфейсы
[Miroboard](https://miro.com/app/board/uXjVNPVFczc=/?share_link_id=485959607245)  
[Figma](https://www.figma.com/file/EoIpkxRrHIX1vrN87qRwh3/Main?type=design&node-id=0%3A1&mode=design&t=qZz0O6mbMLZhHPuO-1)

### Функциональные компоненты решения
- Клиентская часть (web app)
- Хостинг + сервер
- База данных
### Технологии для создания компонентов решения
- Клиентская часть
    - vue + pinia
    - html
    - css + sass
    - js + ts
- Хост + сервер
    - docker
    - python
    - fastapi
    - sqlalchemy
- База данных
    - postgress.db
### Ресурсы
- Еда + вода 
- Мотивация 
- Безграничная любовь от менеджеров 
- sanity
- наклянченный хост
- божья помощь + проповеди пастора Сердюка
### Команда
![Командное фото](/files/project_passport/team/team_photo.jpeg)

<details><summary><h3 style="display:inline">Журавлев Александр Сергеевич</h3></summary>

**Тимлид, разработчик**   

</details>
<details><summary><h3 style="display:inline">Казаков Егор Андреевич</h3></summary>

**ПМ, разработчик**
</details>
<details><summary><h3 style="display:inline">Пучков Иван Сергеевич</h3></summary>

**Главный разработчик**
</details>
<details><summary><h3 style="display:inline">Сердюк Михаил Владимирович</h3></summary>

**Главный аналитик данных, разработчик**
</details>
<details><summary><h3 style="display:inline">Новикова Евгения Константиновна</h3></summary>

**Разработчик, аналитик данных**
</details>

### Риски
- Приложением не будут пользоваться
### MVP
- Анониманое создание конфы для нескольких людей
- У каждого своя доска 
- Создатели имеют полные права на доски, а присоединившиеся ориганиченные
- Тулкит
    - Ручка
    - Курсор 
    - Формы
        - Круг
        - Квадрат
        - Линии
        - Стрелки
    - Текст
- Разные виды (расположения чужих досок)(представления)???
- Создание и завершение конфы   
- Пригласительная ссылка 
- Домашняя страница с кнопкой создания конфы


[Хронология курса "Школа ИТ решений"](CROC_Chronology.md)