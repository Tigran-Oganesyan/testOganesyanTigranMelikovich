# testOganesyanTigranMelikovich
# Оганесян Тигран Меликович
> 1
> >  - Объявить функцию фибоначи и задать параметр (n) в эту функцию. n - число фибонначи
> >     - Объявить две переменные и задать занчение 0 и 1 (предыдущее и следующее)
> >     - вызвать цикл
> >     - в цикле используем метод пузырька
> >     - в цикле объявить переменную (результат) и присваеваем ей значение следующей переменной
> >     - следующей пееремнной присваеваем сумму предыдузей и следуюзих переменных
> >     - предыдущей переменной присваевается переменная результат
> >     - после выхода из цикла возвращаем предыдущую переменную

> 2
> > - Да, можно отправить тело запроса с помощью GET, но оно не должно иметь никакого смысла. Если придать ему значение, анализируя его на сервере и изменяя свой ответ на основе его содержимого, то игнорируется рекомендация в спецификации HTTP/1.1, раздел 4.3: .если метод запроса не включает определенную семантику для тела сущности, то тело сообщения ДОЛЖНО игнорироваться при обработке запроса.

> 3
> > - Тест-кейс № 1. Покупка билета
> > - Шаги:
> >   - Зайти на сайт https://www.tretyakovgallery.ru/
> >   - На главной странице выбирается мероприятие и нажимаем на кнопку "Купить билет"
> >   - Выбираем количестов билетов
> >   - После нажимаем на кнопку "Оформить заказ"
> >   - Проверяется правильно ли выбрали количество билетов
> >   - Нажимаем на кнопку оформить покупки
> >   - Заполняется Имя и Фамилия, почта, а также номер телефона
> >   - Оплата билетов
> > - Ожидаемый результат:
> >   - Открывается сайт, видна кнопка "Купить билет" на главной странице
> >   - При выборе мероприятие переходим на страницу оформления покупки. Выбирается количество билетов. После выбора количества билетов высвечивается справа маленькое окно с количеством билетов и с итоговой суммой.
> >   - После нажатия "оформить заказ" переходим на страницу итогового офрмления. Обязательно нужно ввести Имя, Фамилию, электронную почту и номер телефона. Если один из пунктов не будет заполнен, то этот пунк высвечивается красным.
> >   - После пзаполнения всех данных, ппроисходит переход на оплату данных билетов.

> > - Тест-кейс № 2. Поиск события
> > - Шаги:
> >   - Зайти на сайт https://www.tretyakovgallery.ru/
> >   - На главной странице выбирается иконка поиска
> >   - Появляется форма ввода
> >   - Вводим название события
> >   - Высвечивается данное событие
> > - Ожидаемый результат:
> >   - Открывается сайт
> >   - В правом верхнем ишлу видна лупа. Нажимаем на данную лупу
> >   - Появляется окно где можно ввести текст.Вводится текст и появляются все события связанне с этим названием

> > - Тест-кейс № 3. Проверка навигации и переход на выбранную навигацию
> > - Шаги:
> >   - Зайти на сайт https://www.tretyakovgallery.ru/
> >   - На главной странице высвчивается навигациями
> >   - При наведении на одну из навигаций высвечивается список подпунктов
> >   - Выбирается конкретный подпункт
> >   - Происходит переод на страницу данного подпункта
> > - Ожидаемый результат:
> >   - Открывается сайт
> >   - На главной странице высвечивается навигация
> >   - Наводим на один из пунктов и высвечиваются подпункты даннго пункта.
> >   - Выбираем подпунк и переходим на страницу данного подпункта

> 4
> > - Первое зайти в devTools посмотреть, есть ли ошибки в console
> > - Если нет то заходив во вкладку Network и смотрим передаются ли данные
> > - если статус 200 то все хорошо, если находим , что статус не 200, следовательно у нас ошибка
> > - смотрим какой номер ошибки и разбираемся, что означает эта ошибка
> > - изучив ошиюку можно решить проблему
