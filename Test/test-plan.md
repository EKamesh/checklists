# План тестирования

### Введение

Данный план описывает тестирование приложения "CheckLists".

Требования, предъявляемые к тестировщику:

* умение пользоваться устройством под управлением операционной системы iOS(далее смартфон).

### Объекты тестирования

* Приложение для операционной системы iOS.

Атрибуты качества приложения по ISO 25010:

* функциональность
  * функциональная полнота: приложение должно выполнять все возложенные на нее функции
  * функциональная корректность: приложение должно выполнять все возложенные на нее функции корректно
* производительность
  * временная характеристика: приложение должно открываться не медленнее чем за 30 секунд
* практичность
  * защита от ошибок пользователей: приложение должно выводить сообщения об ошибках если пользователь произвел некорректное действие
* надежность
  * доступность: приложение должно работать при автономной работе смартфомна не менее 5 минут
* мобильность
  * устанавливаемость: приложение должно корректно работать на любом смартфоне с версией iOS выше 9.3 .

### Риски

При некорректной работе приложения возможно некорректное сохранение данных.

### Аспекты тестирования

* возможность создания разделов для объединения однотипных задач;
* возможность редактирования разделов задач;
* возможность удаления разделов задач;
* возможность установки иконки раздела задач;
* возможность создания задач;
* возможность редактирования задач;
* возможность удаления задач;
* возможность установки звукового уведомления и получения уведомления при выключенном приложении;

### Подходы к тестированию

Для тестирования необходим смартфон под управлением операционной системы iOS версии 9.3 и выше.

### Представление результатов

Предоставление результатов требуется описать в следующем виде:

1. Идентификатор
2. Назначение / название
3. Сценарий
4. Ожидаемый результат
5. Фактический результат (заполняется на этапе тестирования)
6. Оценка (заполняется на этапе тестирования)

Тестовые сценарии:

#### Возможность создания разделов для объединения однотипных задач

1. 001

2. Проверка возможности создания разделов для объединения однотипных задач

3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Нажмите на кнопку "+".
   
   3. В появившемся окне нажмите на поле с надписью "Name of the Checklist"

   4. Введите название раздела задач.

   5. Нажмите на кнопку "Done".

4. Приложение вернет вас в начальное меню, где должен отображаться новый созданный раздел.

#### Возможность редактирования разделов задач 

1. 002
2. Проверка возможности редактирования разделов задач 
3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Выберите раздел, который необходимо редактировать.

   3. Нажмите на кнопку ">" на выбранном разделе.

   4. В появившемся окне нажмите на поле с названием раздела.
   
   5. Измените название раздела.
   
   6. Нажмите на поле с названием "Icon".
   
   7. Выберите другую иконку.
   
   8. Нажмите кнопку "Done".

4. Приложение вернет вас в начальное меню, где должна отображаться изменненная задача.


####  Возможность удаления разделов задач

1. 003
2. Проверка возможности удаления разделов задач
3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Выберите раздел, который необходимо удалить.

   3. Проведите пальцем справа налево по выбранному разделу.

   4. В правой части колонки раздела появляется кнопка "Delete".

   5. Нажмите на кнопку "Delete".

4. Выбранный раздел задач должен не отображается.


#### Возможность установки иконки раздела задач

1. 004
2. Проверка возможности установки иконки раздела задач.
3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Нажмите на кнопку "+" или ">" любого раздела задач.

   3. В открывшемся окне нажмите на поле "Icon".

   4. Выберите любую картинку из появившегося списка иконок.

   5. Приложение вернет вас в окно добавления/редактирования раздела задач.
   
   6. Нажмите кнопку "Done".

4. Приложение вернет вас в начальное меню, где слева от изменненого/нового раздела задач должна отображаться выбранная иконка.


#### Возможность добавления новой задачи

1. 005
2. Проверка возможности добавления новой задачи.
3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Нажмите на раздел в котором желаете создать задачу.

   3. В появившемся окне нажмите на кнопку "+".

   4. В появившемся окне нажмите на поле с надписью "Name of the Item".

   5. Введите название задачи.

   6. Нажмите на кнопку "Done".

4. Приложение вернёт вас к списку задач выбранного раздела где должна отображаться новая задача.


#### Возможность редактирования задачи

1. 006
2. Проверка возможности редактирования задачи.
3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Нажмите на раздел в котором желаете отредактировать задачу.
   
   3. В появившемся окне выберите задачу, которую хотите отредактировать.

   4. Нажмите на кнопку ">" на выбранной задаче.

   4. В появившемся окне нажмите на поле с названием задачи.

   5. Измените название задачи.
   
   6. Нажмите на поле с названием "Due Date".
   
   7. В появившемся окне выберите необхоимую дату и время.
   
   8. В поле "Due Date" теперь отображается выбранная дата и время.
   
   9. Нажмите на поле с названием "Remind Me".
   
   10. Переключатель изменил свое состояние.

   11. Нажмите на кнопку "Done".

4. Приложение вернёт вас к списку задач выбранного раздела, где должна отображаться изменненная задача.


####  Возможность удаления задачи

1. 007
2. Проверка возможности удаления задачи
3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Нажмите на раздел в котором желаете удалить задачу.
   
   3. Выберите задачу, которую хотите удалить.

   4. Проведите пальцем справа налево по выбранной задаче.

   5. В правой части колонки задачи появляется кнопка "Delete".

   5. Нажмите на кнопку "Delete".

4. Выбранная задача должна не отображается.


#### Возможность установки звукового уведомления и получения уведомления при выключенном приложении

1. 008
2. Проверка возможности установки звукового уведомления и получения уведомления при выключенном приложении.

3. Произведите следующие шаги:

   1. Запустите приложение.

   2. Нажмите на раздел, в котором хотите установить звуковое уведомление на задаче.

   3. В появившемся окне начните создавать/редактировать задачу. 

   4. В появившемся окне в поле "Remind Me" установите ползунок в состояние "вкл"(зеленый цвет) нажатием на него.
   
   5. Нажмите на поле "Due Date".
   
   6. В появившемся окне выберите дату и время, в которое хотите получить звуковое уведомление.
   
   7. Нажмите на кнопку "Done".
   
   8. Приложение вернет вас в окно со списком задач.
   
   9. Сверните/закройте приложение.

4. В установленное время при закрытом приложении телефон должен издать звуковое уведомление. 

### Вывод

Данные тесты показывают выполнение функциональных требований. Соответствие функциональных требований и тестов:

| Функциональные требования                | ID теста | Успешность прохождения тестов, % |
| ---------------------------------------- | :------: | :------------------------------: |
| Функция создания разделов для объединения однотипных задач | 001 | |
| Функция редактирования разделов задач | 002 |   |
| Функция удаления разделов задач | 003 |   |
| Функция установки иконки раздела задач| 004 |   |
| Функция создания задач | 005 |   |
| Функция редактирования задач | 006 |  |
| Функция удаления задач | 007 |  |
| Функция установки звукового уведомления и получения уведомления при выключенном приложении | 008 |   |
