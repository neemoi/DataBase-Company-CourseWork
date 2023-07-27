# БАЗА ДАННЫХ MSU-PKL-27-2022

**Цель:** Целью курсового проекта является построение реляционной базы данных, основанной на выбранной предметной области.
      
**Задачи курсового проекта:**

      1.Изучить необходимый материал
      2.Провести логическое проектирование реляционной базы данных
      3.Провести физическое проектирование базы данных
      4.Разработать приложение для базы данных

  **Условие задачи:**
      Построить логическую структуру базы данных на уровне взаимосвязей между объектами и на уровне взаимосвязей между атрибутами разных объектов, предварительно определив эти взаимосвязи; подтвердить правильность полученной структуры на экземплярах данных.
      Выполнить нормализацию отношений, для этого необходимо ввести ограничения, определить функциональные зависимости и ключи; привести каждое отношение к третьей нормальной форме.
      Сформулировать следующие запросы и показать правильность их обработки на примерах:

      a. Кто из водителей на данном автомобиле перевозил груз в данную дату? 
      b. Какие предприятия изготавливают данный товар, не выше данной цены?
      c. Кто из владельцев счетов данного банка имеет кредиты на данную дату?
      d. На какой адрес склада был доставлен данный товар, автомобилем с данным номером?
      e. Кто из клиентов (ФИО) получал данный товар и по каким номерам накладных? 
      f. Описать запросы на создание таблиц, индексов, представлений.
      g. Добавить минимум две роли пользователей.
      
**Для создания графического дизайна и разработки Backend части приложения будет использоваться C# (Windows Forms) и MYSQL(PHPMyadmin)**

Графическое изображение, которое будет использовано при построении базы данных 

![Error](https://i.imgur.com/cHXHoKY.png)

# ОБЗОР ГРАФИЧЕСКОГО ПРИЛОЖЕНИЯ

Для работы с базой данных было разработано графическое приложение. 
При запуске приложения открывается окно авторизации, в окне авторизации пользователь вводит свои данные для входа или же создает аккаунт в системе в окне “регистрации”

Окно авторизации 

![Error](https://imgur.com/4XBudXB.png)

Окно регистрации 

![Error](https://imgur.com/ZUhF1EF.png)
      
После успешной авторизации или регистрации пользователя появится соответствующее уведомление

![Error](https://imgur.com/09gJDB5.png)

![Error](https://imgur.com/SzvdvQa.png)

При неправильном вводе данных при авторизации или регистрации появится соответствующая ошибка

![Error](https://imgur.com/4coIqCI.png)

В зависимости от роли после регистрации или авторизации пользователя, открывается окно базы данных. Окно для администратора отличается от окна пользователя 
Окно администратора имеет вкладки таблиц, где можно просмотреть все данные по выбранной таблице, добавить данные, изменить данные, а также выбрать определенные данные с помощью кнопки “Поиск” 

![Error](https://imgur.com/vK5ZvLU.png)

В окне пользователя пользователь также может просматривать данные по таблице выбрав их в подписанном поле “Выбор таблицы”

![Error](https://imgur.com/4ZkvSnK.png)
      
Так же у пользователя есть 5 запросов, связанных с моим курсовым проектом.

![Error](https://imgur.com/YnXcEYA.png)

