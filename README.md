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

## 1.3 Список Test case
**Важно:** Перед выполнением каждого Test case необходимо возвращаться на страницу профессии [«Тестировщик ПО»](https://netology.ru/programs/qa#/order)
> **Валидные значения поля "Имя"**                   
> * из 2 символов на кириллице: Эя
> * из 3 символов на кириллице: Ира
> * с буквой "ё": Пётр
> * латиницей: Mark
> * через пробел: Мира Эмилия
> * через дефис: Мамин-Сибиряк
> * символы на кириллице все Caps Lock: ОЛЬГА
> * символы на кириллице все Num Lock: ольга

> **Валидные значения поля "Телефон"**
> * из 10 цифр без кода страны, без пробелов: 9655458765
> * из 11 цифр начиная с 8, без пробелов: 89655458765
> * из символа + и 10 цифр, без пробелов: +79655458765
> * из 10 цифр без кода страны, с пробелами: 965 545 87 65
> * из 11 цифр начиная с 8, с пробелами: 8 965 545 87 65
> * из символа + и 10 цифр, с пробелами: +7 965 545 87 65
> * из 10 цифр без кода страны, через тире: 965-545-87-65
> * из 11 цифр начиная с 8, через тире: 8-965-545-87-65
> * из символа + и 10 цифр, через тире: +7-965-545-87-65
> * из 10 цифр без кода страны, со скобками, через тире: (965) 545-87-65
> * из 11 цифр начиная с 8, со скобками, через тире: 8 (965) 545-87-65
> * из символа + и 10 цифр, со скобками, через тире: +7 (965) 545-87-65

> **Валидные значения поля "Электронная почта"**
> * Email в нижнем регистре: email@email.ru
> * Email в верхнем регистре: EMAIL@EMAIL.RU
> * Email с цифрами в имени аккаунта: 134@email.ru
> * Email с цифрами в имени аккаунта: 134@email.ru
> *  Email с цифрами в доменной части: email@14email.ru
> * Email с дефисом в имени аккаунта: e-mail@email.ru
> * Email с дефисом в доменной части: email@e-mail.ru
> * Email со знаком подчеркивания в имени аккаунта: e_mail@email.ru
> * Email со знаком подчеркивания в доменной части: email@e_mail.ru
> * Email с точками в имени аккаунта: e.mail@email.ru
> * Email с несколькими точками в доменной части: email@e.mail.ru

### * **Важно:** Перед выполнением каждого Test case необходимо возвращаться на страницу профессии [«Тестировщик ПО»](https://netology.ru/programs/qa#/order)
### 1.3.1 Отправка запроса записи на курс при заполнении формы валидными данными
1. В поле "Имя" ввести валидное значение
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"
   
*Ожидаемый результат:* Обновление страницы, появление сообщения об успешной записи.

### 1.3.2 Отправка запроса записи на курс оставив поле "Имя" пустым
1. Поле "Имя" оставить не заполненным
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Имя" подсвечивается красным, под ним появляется текст ошибки "Обязательное поле".

### 1.3.3 Отправка запроса записи на курс оставив поле "Телефон" пустым
1. В поле "Имя" ввести валидное значение
2. Поле "Телефон" оставить не заполненным
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Телефон" подсвечивается красным, под ним появляется текст ошибки "Обязательное поле".

### 1.3.4 Отправка запроса записи на курс оставив поле "Электронная почта" пустым
1. В поле "Имя" ввести валидное значение
2. В поле "Телефон" ввести валидное значение
3. Поле "Электронная почта" оставить не заполненным
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Обязательное поле".

### 1.3.5 Отправка запроса записи на курс заполнив поле "Имя" НЕ валидным значением, состоящим из 1 буквы
1. В поле "Имя" ввести НЕ валидное значение: Я
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Имя" подсвечивается красным, под ним появляется текст ошибки "Должно быть не короче 2 символов".

### 1.3.6 Отправка запроса записи на курс заполнив поле "Имя" НЕ валидным значением, состоящим из спецсимволов
1. В поле "Имя" ввести НЕ валидное значение: +Х"№@
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Имя" подсвечивается красным, под ним появляется текст ошибки "Должно состоять из букв".

### 1.3.7 Отправка запроса записи на курс заполнив поле "Имя" НЕ валидным значением, состоящим из цифр
1. В поле "Имя" ввести НЕ валидное значение: 12345
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Имя" подсвечивается красным, под ним появляется текст ошибки "Должно состоять из букв".

### 1.3.8 Отправка запроса записи на курс заполнив поле "Телефон" НЕ валидным значением, кириллицей
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести НЕ валидное значение: тырапаыыл
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Номер телефона" подсвечивается красным, под ним появляется текст ошибки "Номер в формате +9 (999) 999-99-99".

### 1.3.9 Отправка запроса записи на курс заполнив поле "Телефон" НЕ валидным значением, латиницей
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести НЕ валидное значение: gfsskgh
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Номер телефона" подсвечивается красным, под ним появляется текст ошибки "Номер в формате +9 (999) 999-99-99".

### 1.3.10 Отправка запроса записи на курс заполнив поле "Телефон" НЕ валидным значением, спецсимволами
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести НЕ валидное значение: +Х"№@
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Номер телефона" подсвечивается красным, под ним появляется текст ошибки "Номер в формате +9 (999) 999-99-99".

### 1.3.11 Отправка запроса записи на курс заполнив поле "Телефон" НЕ валидным значением, состоящим из 9 символов цифрами
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести НЕ валидное значение: 765543655
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Номер телефона" подсвечивается красным, под ним появляется текст ошибки "Номер в формате +9 (999) 999-99-99".

### 1.3.12 Отправка запроса записи на курс заполнив поле "Телефон" НЕ валидным значением, состоящим из 12 символов цифрами
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести НЕ валидное значение: 789645698766
3. В поле "Электронная почта" ввести валидное значение
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Номер телефона" подсвечивается красным, под ним появляется текст ошибки "Номер в формате +9 (999) 999-99-99".

### 1.3.13 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Email без точек в доменной части)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: email@emailru
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.14 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Превышение длины email)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: >320 символов
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.15 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Отсутствие @ в email)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: emailemail.ru
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.16 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Email с пробелами в имени аккаунта)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: e mail@email.ru
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.17 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Email с пробелами в доменной части)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: email@e mail.ru
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.18 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Email без имени аккаунта)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: @email.ru
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.19 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Email без доменной части)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: email@
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

### 1.3.20 Отправка запроса записи на курс заполнив поле "Электронная почта" НЕ валидным значением (Некорректный домен первого уровня)
1. В поле "Имя" ввести валидное значение:
2. В поле "Телефон" ввести валидное значение
3. В поле "Электронная почта" ввести НЕ валидное значение: Некорректный домен первого уровня: допустимо 2-63 букв после точки: .ru или например .americanexpress
4. Нажать на кнопку "Записаться"

*Ожидаемый результат:* поле "Электронная почта" подсвечивается красным, под ним появляется текст ошибки "Неверный email".

# 2. Перечень используемых инструментов с обоснованием выбора.
* **Операционная система (Windows 11 Домашняя для одного языка 22H2):** для запуска программ
* **IDEA (IntelliJ IDEA Community Edition 2023.2):** интегрированная среда разработки
* **Java (OpenJDK 11):** комплект разработчика приложений на языке Java
* **Gradle (gradle-7.6):** система автоматической сборки на языке Java
* **JUnit (junit-jupiter:5.7.0):** фреймворк для модульного тестирования программного обеспечения на языке Java
* **Selenide (selenide:6.17.2):** автоматизированная система тестирования программного обеспечения. Целей использования, создание скриптов, с помощью которых становится проще тестировать работу веб-продуктов
* **Lombok (version 8.2.2):** это основанная на аннотациях библиотека Java, позволяющая сократить шаблонный код
* **Allure (version 2.11.2):** инструмент построения отчётов автотестов, упрощающий их анализ
* **Faker (javafaker:1.0.2):** библиотека, которая позволяет генерировать случайные данные. С ее помощью можно заполнить таблицы в базе данных, построить корректные XML-документы, сформировать JSON-ответы для REST
* **Docker (version 24.0.7):** программная платформа для быстрой разработки, тестирования и развертывания приложений
* **DBeaver (version 23.3.2):** программа для работы с СУБД . С её помощью можно создавать новые базы, изменять и удалять данные в уже существующих, выполнять SQL-запросы
* **Postman (version 10.21.14):** сервис для создания, тестирования, документирования, публикации и обслуживания API
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
24 часа с учетом рисков

   
  
