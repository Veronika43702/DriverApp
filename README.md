# DriverApp

## Навигационное меню
<img src="images/nav-menu.jpg" style="width: 30%">

## Текущие поставки
<img src="images/current_deliveries.jpg" style="width: 30%">


## Текущий заказ
Если заказ еще не активен (статус "заказ размещен"), его можно принять.  
Если заказ активен, кнопка меняет значения с "**взять в работу**" на "**стаутс**".  
При значении
* "**взять в работу**" -> меняется статус заказа
* "**стаутс**" -> переход на фрагмент "Статус заказа"

Срок доставки расчитывается как разница дат (с математическим округлением часов)

<img src="images/current_delivery.jpg" style="width: 30%">


## Статус заказа
Кнопка внизу страницы меняет статус заказа на следующий.  
При разном статусе показывается различная информация.  
Карта неподвижна и любое взаимодейсвтие с ней заблокировано (кроме клика).  
По клику по карте происходит переход на главный фрагмент.

<img src="images/status_started.jpg" style="width: 30%">

## Главная страница
Главный фрагмент с картой.  
Объекты на карте, ориентирование и масштаб карты зависят от статуса активного заказа.  
Если активного заказа нет -> показывается текущее местоположение.  
Доступны кнопки
* центрирования карты на текущем положении
* ориентирования карты по северу

Если есть активный заказ, показывается краткая информация для текущего статуса и кнопка перехода на фрагмент **Статус заказа**.  
Доступна кнопка "info" в верхнем меню справа, которая видна только при наличии активного заказа.  
При нажатии открывается карточка с общей информацией по заказу.

<div style="display: flex;">
  <img src="images/main_started.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/main_order_info.jpg" style="width: 30%">
</div>

## Статус заказа: машина загружена
После загрузки машины виден маршрут от пункта загрузки до пункта разгрузки
<div style="display: flex;">
 <img src="images/status_loaded.jpg" style="width: 30%; margin-right: 10px;">
 <img src="images/main_on_way.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/main_loaded.jpg" style="width: 30%">
</div>


## Статус заказа: в дороге
доступна кнопка "**на стоянке**", которая:
* изменяет статус заказа
* добавляет метку на карте текущего местоположения
* скрывает кнопку перехода на статус "**ТС прибыло на место разрузки**"
* меняет текст кнопки на "**в дороге**", для возвращения к данному статусу

При нескольких стоянок на маршруте на карте и на главном фрагменте будут показаны все стоянки.

<div style="display: flex;">
  <img src="images/status_on_way.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/status_onStand.jpg" style="width: 30%">
</div>

## Поддержка темной темы
<div style="display: flex;">
  <img src="images/night_main.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/night_status_point.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/night_status_route.jpg" style="width: 30%">
</div>

## Статус заказа: загрузить документы
По кнопке доступна загрузка фото из файлов или можно сделать фото через камеру.
Загруженные документы возможно просматривать перед отправкой

<div style="display: flex;">
  <img src="images/status_loadDocuments.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/status_choice_cam_gal.jpg"style="width: 30%; margin-right: 10px;">
  <img src="images/status_documents_uploaded.jpg" style="width: 30%">
</div>

## История заказов (с сортировкой по убыванию даты)
 <img src="images/delivery_history.jpg" style="width: 30%">

## Связь с разработчиком
**Telegram** и **Whatapp** -> открываются мессенджеры с перепиской.  
При нажатии на "**позвонить**" начинается вызов.  

 <img src="images/contacts.jpg" style="width: 30%">


## Мой профиль и изменение пароля
<div style="display: flex;">
<img src="images/profile.jpg"style="width: 30%; margin-right: 10px;">
  <img src="images/profile_changing_pass.jpg" style="width: 30%; margin-right: 10px;">
  <img src="images/profile_pass_changed.jpg" style="width: 30%">
</div>