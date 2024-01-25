# 1. Перечень автоматизируемых сценариев.

## 1.1 Перечень способов перехода на страницу профессии [«Тестировщик ПО»](https://netology.ru/programs/qa) с главной страницы [сайта](https://netology.ru)
**Важно:** Перед выполнением каждого сценария необходимо возвращаться на [главную страницу сайта](https://netology.ru)

### 1.1.1 Переход через раздел "Каталог курсов"
    1) В хедере страницы нажать на кнопку "Каталог курсов"
    2) В выпавшем списке нажать на кнопку "Программирование"
    3) Проскролить страницу с профессиями до специальности "Тестировщик ПО" и кликнуть на наименование специальности 

*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"
### 1.1.2 Переход через раздел "Направления обучения"
#### Первый сценарий
    1) Проскролить страницу до раздела "Направления обучения"
    2) Нажать на кнопку раздела "Полныйт каталог"
    3) Нажать на кнопку "Программирование"
    4) Проскролить страницу с профессиями до специальности "Тестировщик ПО" и кликнуть на наименование специальности
  
*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"

#### Второй сценарий
    1) Проскролить страницу до раздела "Направления обучения"
    2) Нажать на кнопку раздела "Полныйт каталог"
    3) Проскролить страницу с профессиями до специальности "Тестировщик ПО" и кликнуть на наименование специальности
    
*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"

### 1.1.3 Через раздел "Каталог курсов" в футере страницы
#### Первый сценарий
    1) Проскролить страницу до футера страницы
    2) Нажать на кноку "Каталог курсов"
    3) Нажать на кнопку "Программирование"
    4) Проскролить страницу с профессиями до специальности "Тестировщик ПО" и кликнуть на наименование специальности
    
*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"

#### Второй сценарий
    1) Проскролить страницу до футера страницы
    2) Нажать на кноку "Каталог курсов"
    3) Проскролить страницу с профессиями до специальности "Тестировщик ПО" и кликнуть на наименование специальности
    
*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"

### 1.1.4 Через поисковую строку
#### Первый сценарий
    1) В хедере страницы нажать на кнопку "Каталог курсов"
    2) Кликнуть по полю "Какой курс вам нужен?"
    3) Ввести в поле наименование курса "Тестировщик ПО" 
    4) Нажать на кнопку "Найти курс"
    5) Проскролить страницу с профессиями до специальности "Тестировщик ПО" и кликнуть на наименование специальности
    
*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"

#### Второй сценарий
    1) В хедере страницы нажать на кнопку "Каталог курсов"
    2) Кликнуть по полю "Какой курс вам нужен?"
    3) Ввести в поле наименование курса "Тестировщик ПО" 
    4) В всплывющем списке кликнуть на курс "Тестировщик ПО" 
    
*Ожидаемый результат:* открывается страница специальности "Тестировщик ПО"

## 1.2 Сценарий перехода к форме отправки запроса записи на обучение по профессии "Тестировщик ПО" 
    1) Открыть страницу професии "Тестировщик ПО"
    2) Нажать на кнопку "Записатся"
*Ожидаемый результат:* страница автоматически скролится до части с описанием стоимости обучения и формы отправки запроса записи на обучение

## 1.3 Список тестовых случаев




# 2. Перечень используемых инструментов с обоснованием выбора.
    * Операционная система (Windows 11 Домашняя для одного языка 22H2): для запуска программ
    * IDEA (IntelliJ IDEA Community Edition 2023.2): интегрированная среда разработки
    * Java (OpenJDK 11): комплект разработчика приложений на языке Java
    * Gradle (gradle-7.6): система автоматической сборки на языке Java
    * JUnit (junit-jupiter:5.7.0): фреймворк для модульного тестирования программного обеспечения на языке Java
    * Selenide (selenide:6.17.2): автоматизированная система тестирования программного обеспечения. Целей использования, создание скриптов, с помощью которых становится проще тестировать работу веб-продуктов
    * Lombok (version 8.2.2): это основанная на аннотациях библиотека Java, позволяющая сократить шаблонный код
    * Allure (version 2.11.2): инструмент построения отчётов автотестов, упрощающий их анализ
    * Faker (javafaker:1.0.2): библиотека, которая позволяет генерировать случайные данные. С ее помощью можно заполнить таблицы в базе данных, построить корректные XML-документы, сформировать JSON-ответы для REST
    * Docker (version 24.0.7): программная платформа для быстрой разработки, тестирования и развертывания приложений
    * DBeaver (version 23.3.2): программа для работы с СУБД . С её помощью можно создавать новые базы, изменять и удалять данные в уже существующих, выполнять SQL-запросы
    * Postman (version 10.21.14): сервис для создания, тестирования, документирования, публикации и обслуживания API
# 3. Перечень необходимых разрешений, данных и доступов.
    * Разрешение на выполнение автоматизорованного тестирования
    * Доступ к базе данных
    * Доступ к API продукта
    * Тестовые данные для авторизации пользователя (логин, пароль)
# 4. Перечень и описание возможных рисков при автоматизации.
    * Изменение элементов страниц сайта, в связи с этим тесты станут не актуальны. На редактирования кода тестов потребуется дополнительное время
    * Остутствие специальных тестовых меток. На поиск подходящих привязок потребуется дополнительное время
    * Падение сайта или его отдельных страниц под нагрузкой тестирования
# 5. Перечень необходимых специалистов для автоматизации.
    Тестировщик с опытом: 
    * функционального тестирования 
    * автоматизации
# 6. Интервальная оценка с учётом рисков в часах.
    * 24 часа с учетом рисков

   
  
