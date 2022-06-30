<h1><b>Abkhazia-Airbnb App</b></h1>

<h2><b>Описание проекта</b></h2><br />
Туристический сайт для поиска и бронирования проживания, экскурсий, мест в ресторанах/кафе, аренды авто, поиска транспорта для поездки и обратно, информация о предлагаемых для посещения городов. Навигация по сайту возможна через плашку с ссылками в под шапкой, в подвале, при клике "Подробнее" в карточке проживания, экскурсии, авто и т.д., карточка намеренно однотипна для всех типов запросов. Сайт адаптивен, т.е. адекватно выглядит на любых устройствах. Рассмотрим функционал страниц.<br />

<h3><b>Стартовая страница</b></h3><br />
В шапке при выборе города из выпадающего списка или типа поиска при выборе получаем заполненный input с измененным на черный цвет текстом. По умолчанию мы как будто зарегестрированны, однако, можно при клике на "Выйти" из выпадающего списка при клике по профилю "Анастасия" можно ознакомиться с видом при отсутствии регистрации.<br />
Плашка навигации: "Проживание" "Эскурсии и впечатления" "Трансфер" "Аренда авто" "Кухня Абхазии" "Города Абхазии" - при клике переход на соответсвующую страницу.<br />
"Лучшие направления". Слайдер<br />
"Города Абхазии". При наведении на город на карте появляется изображение с какой-то достопримечательностью города. Возможно, имело смысл добавить переход при клике на карточку города, но так как отображение города сделано только как произвольный шаблон, то нет.<br />
"Выбирайте ...". При клике осуществляется переход на страницы "Аренда авто" или "Кухня Абхазии" соответственно.<br />
"Форма". Для заполнения галочка обязательна, при снятии кнопка будет "загашена".<br />
Подвал. Все ссылки кликабельны, переход на страницы "Сообщить о проблеме" и "Форма для предложений" возможен только от сюда.<br />

<h3><b>Сообщить о проблеме</b> и <b>Форма для предложений</b></h3><br />
Страницы для отправки формы, состоят из неё, выглядят идентично.<br />

<h3><b>Проживание</b></h3><br />
Фильтр. При клике на "Частное жилье" в "Категории" выпадает список с подкатегориями. При клике на "Показать все города" выпадает список с возможностью выбора всех городов. Фильтр цены взят с библиотеки Material-UI и подогнан по стилю, выведены значения над ползунками.<br />
Карточки. Для разных условий сделаны разные плашки на картике места, а именно "На сутки / на месяц" и "На сутки". При клике на "Подробнее" переходим на карточку соответствующего места проживания.<br />

<h3><b>Карточка Проживание</b></h3><br />
"Описание-Услуги-Отзывы-Правила и скидки". При клике на плашку отображается соответсвующий раздел. В подразделе "Отзывы" при клике на "Показать все отзывы" открывается модальное окно со всеми отзовами. Модальное окно с "параджой".<br />
"Выбрать номер". В карточке реализован слайдер изображений. При клике на "Подробнее о номере" выпадают подробности о номере, их можно убрать кликнув на "Свернуть". При клике на "Забронировать" переходим на страницу оплаты. В форме бронирования при выборе выпадают календари для дат и калькулятор для пассажиров.<br />
"Где вы будете". Карта сделана на Яндекс.maps. При клике на "Подробнее о городе" переходим на страницу города.<br />
"Похожие отели в Пицунде". Типичный предподвальный слайдер, как и в большинстве карточек этого проекта.<br />

<h3><b>Эскурсии и Впечатления</b></h3><br />
Фильтр.При клике на "Эскурсии" в "Категории" выпадает список с подкатегориями. Выбор городов аналогичен для всех карточек выбора.
Карточки. При клике на "Подробнее" переходим на карточку соответствующего места проживания.<br />


<h3><b>Карточка Эскурсии и Впечатления</b></h3><br />
Работает аналогично карточке "Проживание", имея меньший функционал.<br />


<h3><b>Трансфер</b></h3><br />
Форма. При клике на параметр выпадает список наименований для выбора. Калькуляторы, даты при клике с календаря, время суток, выпадающие списки - тут есть все. При клике на переключатель "В обе стороны" выпадает поле формы для обратного пути. Поля "Откуда", "Куда" и "Пассажиры" заполняются автоматичски из полей сверху.<br />

<h3><b>Трансфер - Оформление заказа</b></h3><br />
Доступно по относительному адресу '/transfer-catalog'. Выбираем параметры трансфера, в том числе и возможность обратного пути. Выбор дат, времени и бронирование билетов справа.<br />
<h3><b>Трансфер - Выбор трансфера</b></h3><br />
Доступно по относительному адресу '/transfer-automobile'.<br />
Форма выбора поездки. При клике на "Изменить маршрут" добавляется форма изменения маршрута. При клике на "Добавить поездку обратно" добавляется форма выбора поездки обратно.<br />
Выбор критериев. При клике на "Индивидуальный" выпадает подменю.<br />
Карточка. При клике на "Выбрать" переходим на страницу Трансфер - Оформление заказа.<br />

<h3><b>Города Абхазии</b></h3><br />
При клике на "Подробнее" переходим на страницу города
<br />
<br />

Страницы Кухни, Аренды авто и их карточек рассписывать смысла не вижу, так как они аналогичны вышеперечисленным по функционалу.
