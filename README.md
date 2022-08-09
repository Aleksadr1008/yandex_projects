<h2 align="center">Проект AB_test</h2>

<p>
<h3  align="center">Первой часть проекта</h3> 
В первой части необходимо проанализировать какие гипотезы следует реализовать в какой последовательности исходя из определённых показателей.
</p>
<p>
<i> Описание: </i> 
дан датасет в котором каждой теориии присвоен ряд характеристик.
Reach охват аудитории, который затронет от внедрения данной гипотезы Impact то насколько сильно изменение повлияет при его внедрении Confidence уверенность, что изменение повлияют то насколько они оценены Efforts стоимость тестировки идеи Изходя из всех этих характеристик нужно просчитать приоритезацию задач
 </p>
<h3  align="center" >Вторая часть проекта</h3>
<p>
Во второй части проекта необходимо проанализировать проведённый А/В тест, на основе имеющихся датасетов (собранных данных за время проведения теста). 
</p>
<p>
<i>Задача</i> стоит в том чтобы ответить на вопрос, повлияли ли внедрённые изменения, и если повлияли то как и насколько (приносят ли они выгоду организации)
</p>
<p>
<i> Описание: </i> 
дано два датасета в 1-ом даны заказы пользователей, есть id каждого пользователя, id заказа, группа (А или В) в которой заказ был выполнен и этим трём характеристикам соответсвует сумма на которую каждый такой заказ был сделан. Второй датасет показывает на каждую дату по каждой группе сколько было посетителей.
</p>

<h2 align="center">Проект AB_test2</h2>
<p>
 <i>Заказчик:</i>
 стартап который работает в сфере продуктов питания.
 </p>
 <p>
 <i>Цель проекта:</i>
 узнать как пользователи доходят до покупки и проанализировать эксперимет компании по внедрению нового шрифта на странице сайта.
 </p>
 <p>
 <i>Описание:</i>
 для работы дан датасет где в котором по каждому пользователю проведённому по сайту собрано (его индентификатор, совершённые пользователем события, время эксперимента, номер группы (в зависимости на какой версии сайта находился участник))
 </p>
 
 <h2 align="center">Проект business_indicators</h2>
 <p>
 Проект изучения причин убыльности рекламной компании Procrastinate Pro+
 </p>
 <p>
 <i>Краткое описание проекта:</i>
 компании Procrastinate Pro+ не смотря на большгие вложения в рекламе терпит убытки. Для анализа есть данные по посещению, покупкам и затратах на рекламу.
</p>
<p>
 <i>Цель:</i>
 выяснить причины убыльности бизнеса.
</p>
<p>
<i>Задачи:</i>
 </p>
 <p>
 - выяснить откуда приходят пользователи и какими устройствами они пользуются;<br>
 - сколько стоит привлечение пользователей из различных рекламных каналов;<br>
 - сколько денег приносит каждый клиент;<br>
 - когда расходы на привлечение клиента окупаются;<br>
 - какие факторы мешают привлечению клиентов.
</p>
<p>
 <i>Описание (даны три дата фрейма):</i>
 </p>
<p>
 - посещения клиентов (id пользователя, страна, устройство, канал, время окончания и начала сессии);<br>
- заказы пользоватетелей (id пользователя, дата заказа, сумма заказа );<br>
- затраты на рекламу по каналам (дата затрат, канал затрат, количество затрат).
</p>

 <i>План:</i>
</p>
<p>
- проверить данные на корректность создать функции для оптимизации дальнейшей работы;<br>
- провести исследовательский анализ (создать профили пользователей, проанализировать приход платящих пользователей на сайт по странам, по девайсам, по каналам);<br>
- провести маркетинговый анализ (расчитать САС);<br>
- оценить окупаемость рекламы (создать графики LTV, CAC и ROI в разрезе стран, девайсов и каналов, выявит проблемы);<br>
- сделать выводы по всему проекту и предположить почему реклама не окупается.
</p>

<h2 align="center">Проект data_analysis</h2>
 <p>
 <i>Заказчик:</i>
 компания "Ненужные вещи". У компании есть приложение где пользователи могут продавать и покупать вещи друг друга
 </p>
 <p>
 <i>Краткое описание проекта:</i>
 заказчик хочет определить, какая основная категория пользователей, какие есть с смежные категории, посмотреть на их различие в поведении по метрикам.
</p>
<p>
 <i>Вопросы заказчика:</i><br>
Какие пользователи склонны часто возвращаться в мобильное приложение?<br>
Какие пользователи часто делают целевое событие (contacts_show)?<br>
Как различается время между распространенными событиями пользователей, (например, различаются ли пользователи по группам на основе времени, которое проходит с момента первого использования мобильного приложения и до использования функции поиска)?
</p>
<p>
 <i>Задача выделить (отметить) группы пользователей, которые различаются по метрикам:</i>
</p>
<p>
- Retantion Rate;<br>
- Время в приложении;<br>
- Частота совершения событий;<br>
- Конверсия в целевое действие CONTACTS_SHOW.<br>
<i> Данная задача выполняется для прорабоки действий для повышения вовлечённости пользователей. В последствии необходимо выдвинуть гипотезы как можно оптимизировать пути пользователей, выдвинуть идеи для экспериментов</i>
</p>
 <p>
  <i>Описание имеющихся данных:</i>
</p>
<p>
 В датасетах содержатся данные пользователей, впервые совершивших действия в приложении после 7 октября 2019 года.
 <i>Дано 2 датасета:</i> <br>
- датасет mobile_sources.csv содержит колонки: userId — идентификатор пользователя source — источник, с которого пользователь установил приложение;<br>
- датасет mobile_sources.csv содержит колонки: userId — идентификатор пользователя source — источник, с которого пользователь установил приложение.<br>
 </p>
 <p>
 <i>Расшифровки событий:</i>
 advert_open — открытие карточки объявления photos_show — просмотр фотографий в объявлении; tips_show — пользователь увидел рекомендованные объявления; tips_click — пользователь кликнул по рекомендованному объявлению; contacts_show и show_contacts — пользователь нажал на кнопку "посмотреть номер телефона" на карточке объявления; contacts_call — пользователь позвонил по номеру телефона на карточке объявления map — пользователь открыл карту размещенных объявлений; search_1 — search_7 — разные события, связанные с поиском по сайту favorites_add — добавление объявления в избранное. <br>
</p>

<h2 align="center">Проект ML</h2> 
<p>
 <i>Краткое описание проекта:</i>
</p>
<p>
Сеть фитнес-центров «Культурист-датасаентист» разрабатывает стратегию взаимодействия с клиентами на основе аналитических данных.
</p>
 <p>
  <i>Описание имеющихся данных:</i>
</p>
<p>
есть датасет с признаками по клиентам пришедших в клуб (пол, место проживания, партнёрство с клубом, использование акции "приведи друга", наличие контактного телефона, возраст, время с первого посещения, длительность абонимента, срок окончания абонемента, факт посещения груповых занятий, частота посещения в неделю, выручка от других услуг фитнеса ) и дана целевая переменная (факт оттока)
</p>
<p>
<i>Цель проекта:</i>
</p>
<p>
 провести анализ и подготовить план действий по удержанию клиентов.
</p>
<p>
<i>Задачи проекта:</i>
</p>
<p>
- научиться прогнозировать вероятность оттока (на уровне следующего месяца) для каждого клиента;
- сформировать типичные портреты клиентов: выделить несколько наиболее ярких групп и охарактеризовать их основные свойства; <br>
- проанализировать основные признаки, наиболее сильно влияющие на отток; сформулировать основные выводы и разработать рекомендации по повышению качества работы с клиентами.<br>
</p>
























