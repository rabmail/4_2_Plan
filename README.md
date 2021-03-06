# Тестирование возможности записи на обучение профессии "Тестировщик ПО" на сайте netology.ru

## Перечень автоматизируемых сценариев

### 1. Запись на обучение посредством "Каталога курсов" на главной странице.

    * зайти на сайт https://netology.ru;
    
![](/images/img1.png)

- нажать кнопку "Каталог курсов"

   
![](/images/img2.png)

- слева выбрать "Программирование"
 
![](/images/img3.png)

- нажать "Тестировщик ПО"

![](/images/img4.png)

- нажать кнопку "Записатся"

### 2. Запись на обучение посредством кнопки "Neo" на главной странице.

![](/images/img2_1.png)

- нажать кнопку "Neo"

![](/images/img2_2.png)

- нажать кнопку "Записатся"

### 3. Запись на обучение посредством кнопки раздела "Изучай актуальные темы" на главной странице.

![](/images/img3_1.png)

- пролистать страницу ло раздела "Изучай актуальные темы", выбрать "Программирование"  

![](/images/img3.png)

- нажать "Тестировщик ПО"


![](/images/img4.png)

- нажать кнопку "Записатся"


## Тестовые данные

### Позитивный сценарий:
1. Имя - Василий
2. Номер телефона - 8-910-111-22-33

### Негативный сценарий:
1. Имя - 123
2. Имя -$%$
3. Номер телефона - 8-910-111-22-33 -3
4. Номер телефона - 8-910-111-22-3

__Формы для ввода данных__
 
 * по первому и третьему сценарию 
 
![](/images/img2_3.png)

* по второму сценарию 

* ![](/images/img5.png)

## Перечень используемых инструментов с обоснованием выбора

**_JetBrains IntelliJ IDEA_**  – интегрированная среда разработки программного обеспечения для многих языков программирования, в частности Java, JavaScript, Python. 

**_Java, версия 11_** – строго типизированный объектно-ориентированный язык программирования общего назначения.

**_Gradle_** — система автоматической сборки, которую используют для упрощения работы с Java.

**_JUnit5_** –библиотека для модульного тестирования программного обеспечения.

**_Selenide_** – фреймворк для автоматизированного тестирования веб-приложений.

**_Allure_** – фреймворк для создания отчетов автотестов.

**_Lombok_** – библиотека, позволяющая сократить количество написанного кода.

**Выбор обоснован - умением исполнителя работать с данными инструментами.**

## Перечень необходимых разрешений/данных/доступов

*Разрещение на тестирование

*Доступ к БД или возможность получать данные о результате (get, post)

## Перечень и описание возможных рисков при автоматизации

*Попадание тестовых данных в реальную БД

*Проблемы с подключением 

## Перечень необходимых специалистов для автоматизации

_QA - инженер_

## Интервальная оценка с учётом рисков (в часах)

_8 часов_
