## 1.62 (25.05.2025)

### Серверная машина.
— Исправлена ошибка с базами данных жалоб (данные сохранены) и кейсов (утеряны данные);
— Исправлена ошибка с сетью из-за которой не было доступа к серверной машине по всем фронтам.


## 1.61 (24.05.2025)

### Серверная машина.
— Актуализировано обновление [1.28](https://github.com/AgeTime-mc/dev/blob/main/CHANGELOG.md#128-24042025) на текущую серверную машину где развёрнут сервер.


## 1.60 (24.05.2025)

### Права.
— Исправлена ошибка поддержки кодовой базы на версии игры 1.21.5.
### Скины.
— Исправлена ошибка обновления скинов на игровых/технических режимах;  
— Исправлена ошибка отсутствия ограничения на использование команд и смены скинов (без задержки использований функций плагина);  
— Исправлены некритические ошибки в зависимостях;  
— Исправлены ошибки отсутствия корректных ответов в некоторых сообщениях;  
— Оптимизирован алгоритм генерации скинов;  
— Оптимизировано взаимодействие с сообщениями;  
— Оптимизировано обновление скинов.


## 1.59 (23.05.2025)

### Серверная машина.
— Полностью исправлена ошибка с очисткой логов режимов из обновления [1.58](https://github.com/AgeTime-mc/dev/blob/main/CHANGELOG.md#158-23052025).


## 1.58 (23.05.2025)

### Серверная машина.
— Попытка исправления ошибок с очистками логов режимов (через N промежуток/количество файлов).

> [!NOTE] 
> Полноценное исправление ошибки будет выполнено ночью с 23 по 24 мая 2025 года.

> [!WARNING]
> Данная ошибка являлось причиной отсутствия пространства на серверной машине, по причине которой сервер переодически отключался.


## 1.57 (22.05.2025)

### Серверная машина.
— Исправлена ошибка с записью логов режимов;  
— Перенесены игровые данные на старую серверную машину.


## 1.56 (20.05.2025)

### Авторизация.
— Исправлена ошибка в ссылке относящейся к гайду по привязке игрового аккаунта в боте, которая возникает когда игрок пишет непонятную абракадабру в чат с ботом;  
— Исправлена ошибка некорректного отображения сообщения с гайдом по привязке игрового аккаунта в боте, которая должна возникать когда игрок пишет непонятную абракадабру в чат с ботом, но возникала при нажатии на любую кнопку на клавиатуре внутри системы бота.

> [!NOTE] 
> Полноценный залив обновы на сервер произойдёт на глобальное летнее обновление от 2025 года.


## 1.55 (20.05.2025)

### Сайт.
— Страница со списком администрации была удалена;  
— Страница с правилами была удалена;  
— Удалены отключённые информационные табло на всех страничках сайта (в том числе на главной и покупки);  
— Удалены все связанные элементы со списком последних покупок.

> [!WARNING] 
> Некоторые страницы были перенесены в другие отделы проекта.

> [!NOTE] 
> Отключение и дальнейшее удаление списка последних покупок сделано по параметрам безопасности данных игроков, в связи с тем, что некоторые логгеры получают информацию из данной ленты в своих целях (для попыток взлома игровых аккаунтов на нашем сервере и смежных серверах на которых играет игрок).


## 1.54 (20.05.2025)

### Анархия "PvP".

#### Кейсы.
— Актуализирована лицензия на разработку, она переведена в режим лицензии на срок lifetime (вечная);  
— Добавлена поддержка новых анимаций.

### Серверная машина.
— Осуществлены бэкапы всех данных режимов для их дальнейшего переноса на старую серверную машину.

> [!NOTE] 
> Ранее проект находился на этой серверной машине, но из-за частых падений со стороны хостинг провайдера съехал с неё, при этом учитывался факт её мощности в 4 раза по сравнению с той, на которой стояли в последний месяц (учитываются все дни т.е. время жизни серверной машины).


## 1.53 (19.05.2025)

### Социальные сети.
— Актуализированы частично ссылки на сайт проекта;  
— Отключена кнопка перехода на сайт для покупки товаров на главной страничке сообщества во ВКонтакте.


## 1.52 (19.05.2025)

### Анархия "Classic".
— Переведена на технические работы.
### Бот.
— Обновлена версия кодовой базы скрипта связи с технической поддержкой.
### Версии.
— Попытка отката обновления, связанного с пакетным обработчиком версии [1.43](https://github.com/AgeTime-mc/dev/blob/main/CHANGELOG.md#143-04052025), была предпринята, так как, как показала практика, оно не было полностью реализовано и лишь нагружало серверную машину, увеличивая пинг.
### Серверная машина.
— Исправлена ошибка отсутствия пространства для хранения данных.
### Социальные сети.
— Добавлена документация по привязке игрового аккаунта к боту в мессенджерах;  
— Добавлены разделы проекта: жалобы и снятие игровых блокировок, подача заявки в команду проекта (доступны привилегии: модераторские, медийные, поддержка, технический администратор и спонсор), недоработки и предложения;  
— Изменено название канала в Telegram (ранее он являлся основным);  
— Изменено название паблика во ВКонтакте;  
— Осуществлены переносы игровых правил проекта с сайта под будущее обновление.


> [!NOTE]
> Перенос разделов проекта и его правил осуществляется в рамках глобального летнего обновления от 2025 года.

> [!NOTE]
> Полноценная реализация пакетного обработчика будет осуществлено после глобального летнего обновления от 2025 года. Его наличие необходимо, так как он снизит пинг игроков и уменьшит нагрузку на серверную машину, но без полноценной работоспособности он будет являться огромной проблемой сервера.

> [!WARNING]
> Первопричины ошибки отсутствия пространства для хранения данных на серверной машины исправлены в обновлении [1.58](https://github.com/AgeTime-mc/dev/blob/main/CHANGELOG.md#158-23052025).


## 1.51 (18.05.2025)

### Версии.
— Добавлена поддержка пакетных данных последних версий игры;  
— Исправлена ошибка передачи пакетных данных между версиями.


## 1.50 (14.05.2025)

### Анархия "Classic".

#### Ядро.
— Изучены ошибки некорректной работоспособности вайт-листа и кэшированием данных пользователей по их [уникальным идентификаторам (UUID)](https://minecraft.wiki/w/UUID).

> [!NOTE] 
> Из-за наличия обильного количества строк кода в ядре и наших изменений - изучение уже является великим прогрессом.


## 1.49 (12.05.2025)

### Анархия "PvP".

#### Анти-чит.
— Исправлена ошибка взаимодействия с доступными командами модерации;  
— Исправлена ошибка получения уведомлений модераторам.
#### Голограммы.
— Переформулированы нечитабельные отделы «информационно-приветственной» голограммы.
#### Кейсы.
— Изменена платформа на «5x5» (речь о блоках, по осям `x` и `z`) вместо «7x7» для открытия «кейса с донатом»;  
— Изменено количество возможных открытий «кейса с донатом»;  
— Изменены анимации для всех кейсов на самые передовые разработки (аххахахах);  
— Изменены скрытые сундуки с предметами в платформе «5x5»;  
— Исправлена ошибка выдачи привилегий в «бесплатном кейсе»;  
— Исправлена ошибка для локации «кейса с ресурсами»;  
— Исправлена ошибка названия предмета переходника к кейсам в меню «бесплатного кейса».
#### Киты.
— Исправлены ошибки связанные с описаниями и зачарования предметов из кита «самурая».
#### Меню.
— Исправлена ошибка информации о времени в меню «наград».
#### Регионы.
— Исправлена ошибки в регионах на карте мира спавна: появление мобов, урон по мобам, взаимодействие с сундуками и иными игровыми блоками (речь о люках и т.д.), а также с режимом pvp (на определённых участках).


## 1.48 (09.05.2025)

### Анархия "Classic".

#### Регионы.
— Исправлена ошибка взаимодействия с регионами на карте спавна (использование предметов, опадение листвы и т.д.).


## 1.47 (08.05.2025)

#### Сайт.
— Исправлена ошибка с информацией о режимах (получение онлайна и информации о пользователях).


## 1.46 (08.05.2025)

#### Сайт.
— Исправлена ошибка с взаимодействием режима «Анархии "PvP"»;  
— Исправлена ошибка с информацией в сообщении выдачи награды.


## 1.45 (04.05.2025)

### Анархия "Classic".

#### Авто-сообщения.
— Исправлены ссылки в сообщениях;  
— Убрана неактуальная информация.  

### Хаб.

#### Скоребоард.
— Скорректировали текстовые поля в борде.


## 1.44 (04.05.2025)

### Анархия "Classic".

#### Авто-шахта.
— Исправлена ошибка спама информации для разработчиков.  
#### Анти-чит.
— Актуализированы настройки с режима «Анархия "PvP"»;  
— Исправлены ошибки с переводами сообщений в чате.  
#### Версии.
— Исправлена ошибка спама информации в чате для игроков.  
#### Голограммы.
— Актуализированы оптимизированные настройки с режима «Анархия "PvP"».  
#### Миры.
— Откат карты мира спавна на полмесяца тому назад, когда не было инцидентов с заходами игроков на режим.  
#### Наборы.
— Исправлена ошибка выдачи несуществующего набора при заходе на сервер.  

### Анархия "PvP".

#### Анти-чит.
— Включён режим детальной информации для разработчиков, чтобы мы смогли обновить АЧ в ближайшие времена;  
— Исправлено управление анти-читом для сотрудников.  


## 1.43 (04.05.2025)

### Анти-бот.
— Исправлена ошибка взаимодействия с чатом после выхода с проверки на бота;  
— Теперь капча появится только, если система обнаружит подозрительное подключение (капча для обычных игроков пропадёт, что снизит негодование на счёт этих сложных буковок хе-хе).  
### Версии.
— Добавлено отключение игрока от сервера за спам игровыми командами (без ограничений на использование самих игровых команд);  
— Исправлена ошибка из-за которой информация о позиции игрока могла передаваться серверу некорректно;  
— Обновлён пакетный обработчик версий из-за которого был пинг выше, чем ранее;  
— Откат оптимизированного подключения к серверу (как оказалось из-за него пинг был высоким).  
### Таблист.
— Исправлена ошибка с неизменяемой информацией в таблисте;  
— Оптимизировано обновление таблиста.


## 1.42 (04.05.2025)

### Анархия "Classic".

#### Миры.
— Все игровые карты вайпнуты, а их сиды изменены.
#### Наборы.
— Вайпнуты ещё раз в ходе игрокового наплыва.
#### Регионы.
— Добавлены на карту мира спавн;  
— Удалены регионы игроков в ходе очередного инцидента.


## 1.41 (04.05.2025)

### Анархия "Classic".

#### Предметы.
— Добавлено описание к предметам которое не было добавлено техническим администратором;  
— Исправлена ошибка запрещающая использование предметов не мешающих красотам карты мира спавна;  
— Исправлена ошибка разрешающая использование предметов ломающих карту мира спавна;  
— Исправлены ошибки в описании предметов.  
#### Спавн.
— Скорректированы координаты точки появления по осям: x, z, yaw и pitch.


## 1.40 (03.05.2025)

### Анархия "Classic".

#### Голограммы.
— Исправили ошибку отсутствия голограмм на карте мира "спавн".
#### Предметы.
— Произвели откат данных, дабы все описания и работоспособность предметов вернулось на круги своя.
#### Скоребоард.
— Исправили ошибку из-за которой мог показываться устаревший боард.
#### Спавн.
— Исправили точку появления игрочков.
#### Таблист.
— Исправили ошибку с задвоением текста в таблисте.
#### Чат.
— Исправили цвета сообщений в чате.


## 1.39 (03.05.2025)

### Защита.
— Исправлена ошибка из-за которой на режимах сломалось всё.
### Перезагрузка.
— Отключена автоматическая перезагрузка для режима «Анархия "Classic"».



## 1.38 (03.05.2025)

### Сеть.
— В связи с пингом выше >30 у игроков из РФ перенастроили параметры сети, дабы у игроков из РФ пинг стал в 2 - 3 раза меньше.


## 1.37 (02.05.2025)

### Анархия "Classic".

#### Версии.  
— Актуализированы обновления с режима «Хаб».
#### Меню.
— Исправлена ошибка из-за которой можно было абузить награды и скупки предметов.
#### Таблист.  
— Актуализированы обновления с режима «Хаб».


## 1.36 (02.05.2025)

### Хаб.

#### Версии.  
— Исправлена ошибка появления неигровых персонажей в таблисте.  
#### Таблист.  
— Исправлена ошибка взаимодействия чата на версиях игры 1.20/1.21;  
— Оптимизировано взаимодействие с пакетными данными при заходе игрока на режим.  


## 1.35 (30.04.2025)

### Анархия "Classic".

#### Миры.
— На карте мира "спавн" увеличено количество кэшированных данных на N (условность) промежуток времени;  
— Оптимизация хранения данных об игроков;  
— Отключены предупреждения о некорректной загрузке частичных данных миров (debug для разработчиков);  
— Теперь на карте мира "спавн" отключены игровые карты (с помощью которых можно было сложить сервер как пирожок, это так, к слову).  
#### Неигровые персонажи (NPC).
— Исправлена потенциальная ошибка из-за которой могли неработать некоторые NPC по направлениям осей yaw/pitch.  


## 1.34 (30.04.2025)

### Хаб.

#### Миры.
— Количество пред-загружаемых чанков уменьшено в 2 раза (с 12 до 6 чанков) дабы уменьшить пинг у игроков;  
— Отключено кэширование данных на карте мира;  
— Отключены предупреждения о перегрузках данных полученных от игроков по карте мира;  
— Радиус обзора игрока по умолчанию уменьшен с 6 до 4 чанков, а также установлен для всех игровых событий на это значение, за исключением прогрузки NPC.  
#### Неигровые персонажи (NPC).
— Увеличена дистанция на которой видно NPC в 2 раза (с 64 до 128 блоков).  


## 1.33 (27.04.2025)

### Анархия "PvP".

#### Меню.
— Исправлена ошибка из-за которой можно было брать награду в `/reward` под номером №7 бесконечное количество раз;  
— Исправлена ошибка некорректного отображения информации о донате в меню "Привилегией";  
— Исправлена ошибка отображения атрибутов предмета возврата обратно в меню "Бесплатный опыт";  
— Исправлена ошибка с номером последней награды в `/reward`;  
— Исправлена ошибка с отсутствием команды `/don` для меню "Привилегий";  
— Удалены проверки на наличие определённых прав для меню "Привилегий";


## 1.32 (26.04.2025)

### Анархия "PvP".

#### Миры.
— Исправлена ошибка из-за которой игровые миры ад и энд не работали. 


## 1.31 (24.04.2025)

— Отключён глобальный режим по разрешённым командам;  
— Удалены глобальные задержки на чат и команды;


## 1.30 (24.04.2025)

### Анархия "Classic".

#### Миры.
— Исправлена ошибка из-за которой игровые миры ад и энд не работали.  
#### Предметы.
— Удалены тестовые регионы из-за которых предметы могли не работать;  
— Добавлен игровой мир спавна в котором предметы теперь не работают, дабы не сломать этот чёртов спавн как в прошлый раз;  
— Отключены тестовые предметы (опять для разработчиков хрень);  
#### Спавнера.
— Очищена информация о спавнерах, которая ломала карты.  
#### Кейсы.
— Исправлены локации для точек с кейсами.  
#### Скупщик.
— Данные игроков после инцидента были очищены.  
#### Эвенты.
— Исправлена ошибка из-за которой не работали эвенты: клад и сокровища пиратов.  
#### Регионы.
— Теперь на карте спавна регион нельзя создать, как это было можно ранее забагать.  

### Хаб.

#### Таблист.
— Исправлена ошибка (финальная) сортировки игроков по приоритизации.


## 1.29 (24.04.2025)

### Анархия "Classic".
— Завершён перенос данных на новый хостинг.

### Хаб.

#### Голограммы.
— Исправлены ошибки в названии голограмм;  
— Обновлен домен сайта;
#### Чат.
— Временно отключён в связи с багами.  
#### Неигровые персонажи (NPC).
— Скорректированы координаты всех NPC по осям: x, z, yaw и pitch.


## 1.28 (24.04.2025)

— Исправлена ошибка из-за которой режимы не перезагружались автоматически.


## 1.27 (24.04.2025)

### Анархия "PvP".

#### Реклама.
— Изменена сортировка строк, дабы не дублировались;  
— Исправлена ошибка в команде на техническую поддержку (обновление [1.24](https://github.com/AgeTime-mc/dev/blob/main/CHANGELOG.md#124-23042025));  
— Исправлена ссылка на техническую поддержку на другой строке (их две - пон, пон);  


## 1.26 (24.04.2025)

### Анархия "PvP".

#### Реклама.
— Отключена реклама вечных скидок при заходе на режим;  


## 1.25 (24.04.2025)

### Анархия "PvP".

#### Ссылки.
— Исправлена ссылка на техническую поддержку;  
— Обновлён домен сайта;  
— Убрана вечная информация о скидках на сайте;  


## 1.24 (23.04.2025)

### Анархия "PvP".

#### Авто-шахта.
— Добавлен разделитель между строками в голограмме;  
#### Варпы.
— Исправлены ошибки в переводах;  
#### Жалобы.
— Исправлены мелкие ошибки в интерфейсе для сотрудников;  
#### Команды.
— Отключены команды для зависимостей (библиотек), которые предусмотрены для debug режима (кратко - штука для разработчиков);  
— Переработана команда `/hub`, которая работает теперь на всех режимах благодаря удалению команды внутри режима (короче, у нас их было 2 штуки, потому что человек перепутал всё, а разработчик исправил это перепутанье, сделав всё как надо);  
#### Наборы.
— Исправлена ошибка выдачи несуществующего набора при заходе на сервер;  
#### Скоребоард.
— Обновлены домены сайта;  
— Удалены жирные цвета в названии режима;
#### Ссылки.
— Исправлены ссылки на социальные сети в команде `/links`;  
— Потенциальное исправление ссылки на правила в очевидной команде `/rules`;  
— Исправлена ссылка на сообщество ВКонтакте через команду `/vk`;  
— Попытка фиксов ссылки на несуществующий дискорд сервер через команду `/discord`;  
— Удалены неизвестные разработчику ссылки через команду `/support` на неизвестные для него ресурсы, ведь там должна располагаться поддержка, поэтому она теперь там расположена стопудово;  
#### Статистика.
— Теперь мы не сохраняем сброшенную статистику топов дабы не терять производительность и просрацию диска серверной машинки, а то она деняк стоит вщт;  
#### Таблист.
— Удалены жирные цвета в названии режима;  
#### Чат.
— Добавлены переводы на сообщения связанные на взаимодействие с игровым чатом (команды: `/reply`, `/msg` и др.; ошибки и различные предупреждения);  
— Обновлены ссылки на домен в различных сообщениях;  

### Хаб.

#### Реклама.
— Изменена команда для скрытия босс-бара на `/bar` (хотя прав у вас всё равно нету хахахах, но написать надо же);  
— Исправлена ссылка на техническую поддержку;  
#### Скоребоард.
— Изменена команда для скрытия босс-бара на `/board` (прав естественно нету - привет Матвею передайте);  
— Отключён капс-лок (большие буквы) на название режима;  
— Переформулирована информация о режиме;  
— Убран жирный шрифт в названии режима;   
#### Таблист.
— Изменены названия режима;  
— Информация сжата по количеству строк через разделитель;  


## 1.23 (23.04.2025)

#### Анти-чит.
— Исправлены мелкие ошибки связанные с оповещениями сотрудников.


## 1.22 (23.04.2025)

#### Версии.
— Удалена поддержка версий ниже 1.16.4/5, благодаря чему пинг теперь будет более стабильным и нагрузка на серверную машину уменьшится.
#### Плейсхолдеры.
— Оптимизирован алгоритм замены сообщений.


## 1.21 (23.04.2025)

### Хаб.

#### Таб.
— Исправлена ошибка приоритизации привилегий (сортировка по значимости).


## 1.20 (23.04.2025)

### Хаб.

#### Таб.
— Исправлена ошибка задвоения символов между числом онлайна и строкой;  
— Исправлена ошибка отображения суффиксов;  


## 1.19 (23.04.2025)

#### Версии.
— Исправлена ошибка из-за которой пинг мог быть выше на 10-20 мс.;  
— Исправлена ошибка из-за которой после телепорта игрок мог быть невидимым для некоторых игровых версий;  
— Обновлены библиотеки для поддержки мульти-версий;  
#### Скины.
— Оптимизирована генерация сообщений в меню.  


## 1.18 (23.04.2025)

### Технические работы.
— Скорректированы ссылки на социальные сети.


## 1.17 (23.04.2024)

### Серверная машина.
— Теперь данные разделены между серверными машинами, дабы снизить на них нагрузку.


## 1.16 (23.04.2024)

### Серверная машина.
— Обновили структурированные части для автоматической сборки серверов;  
— Обновлены уведомления об авторизациях со всех локаций (детальная информация и исправлены мелкие ошибки);  
— Улучшена защита от внешних воздействий на сервер (попытки взлома);  

__________________________________________
## 1.15 (22.04.2025)

Осуществлёны бэкапы данных для переноса на другой хостинг.


## 1.14 (17.04.2025)

Обновлены версии всех библиотек (оптимизация, фиксы ошибок и т.д. - база).


## 1.13 (17.04.2025)

### Анархия "Classic".

#### Варпы.
— Удалены точки игроков возникшие в ходе инцидента с доступом к режиму;
#### Эвенты.
— Удалены активные точки, которые не исчезли в ходе остановки режима (так бы часть мира отжали у бедненьких игрочков);
#### Предметы.
— Исправлены использованные трапки на спавне (ломатели карт сраные);
#### Наборы.
— Очищены данные о людях взявших киты на режиме в ходе инцидента;


## 1.12 (17.04.2025; ⚠️⚠️⚠️ Основная партия изменений датируется 06.04.2025 по настоящее)

### Анархия "Classic".

#### Авто-шахта.
— Исправлена ошибка неработоспособности;
#### Предметы.  
— Переработаны все уникальные предметы;  
— Исправлена ошибка работоспособности в игровых мирах, теперь на карте мира "спавн" большая часть не работает;  
— Уменьшены задержки перед повторным использованием;  
#### Спавн.
— Исправлены координаты точки спавна;  
#### Зачарования.
— Перестали обитать на этом режиме;  
#### Права.
— Добавлена актуальная структура прав на основании которой работает режим;  
— Исправлена ошибка из-за которой админ не имел всех прав на сервер (аххахахахах);  
#### Эвенты.
— Добавлены необходимые эвенты для работы режима;


### Анархия "PvP".

#### Права.
— Отделены игроки и их права от других режимов, дабы не было пересечения по задумке автора;  
— Исправлена ошибка из-за которой админ не имел всех прав на сервер (аххахахахах);  

### Хаб.

#### Права.
— Актуализирована структура прав на основании которой работает связка режимов;


## 1.11 (17.04.2025)

### Безопасность.
— Исправлена ошибка из-за которой новые данные не сохранялись.

## 1.10 (05.04.2025)

### Авторизация.
— Откат обновления [1.8](https://github.com/AgeTime-mc/dev/blob/main/CHANGELOG.md#18-05042025) (Теперь игрок в мире появляется в режиме "спектатора");

## 1.9 (05.04.2025)

### Анархия "Classic".
— Обновлены [сиды](https://minecraft.fandom.com/wiki/Seeds) игровых карт;  
— Повторно удалены все игровые карты дабы произошла перегенерация с новыми [сидами](https://minecraft.fandom.com/wiki/Seeds) (умные найдут применение одинаковым картам на анархиях);  

### Анархия "PvP".
— Команад `/sit` была удалена;  
— Оптимизировано взаимодействие c таблистом на версии 1.16 и выше;

### Хаб.
— Подключена общая система прав вместе с режимом "Анархия Classic".

## 1.8 (05.04.2025)

### Авторизация.
— Свет в мире был уменьшен в 3 раза;  
— Теперь игрок в мире появляется в режиме "спектатора";  
— Титульное сообщение после успешной авторизации пропадает моментально;  
— Минимальная длина пароля изменена с 4 до 6 символов;  
— Время на авторизация увеличено с 2 минут до 2 минут и 30 секунд;  
— Время для регистрации нового аккаунта увеличено с 24 до 48 часов;  

### Бот.
— Скорректированы доступные слова для использования бота (вернули фразу `!бот`);  

### Технические работы.
— Скорректированы префиксы в сообщениях на все режимы;  
— Исправлены ошибки переводов сообщений технических работ;  

### Фильтрация.
— Удалены лишние символы и новые строки в сообщениях фильтрации;  
— Добавлены переводы на все сообщения с ошибками подключений, а также они были скорректированы;  
— Время повторной проверки на бота увеличено с 2 до 7 дней (теперь не будете проходить капчу каждые 2 дня);  
— Теперь проверка на падение происходит быстрее (время уменьшено с 5 до 2.5 секунд);  
— Отключены команды `/find` и `/send`;  

### Хаб.
— Добавлены переводы на сообщения;  
— Теперь команду хаба нельзя использовать в хабе, ибо он уже там находится (какого фига?);  
— Увеличена задержка на использование команды `/hub` с 1 до 3 секунд;  

## 1.7 (05.04.2025)

### Сайт.
— Добавлена доплата для привилегий;  
— Исправлена ошибка отображения онлайна проекта;

## 1.6 (04.04.2025)

### Авторизация.
— Добавлены переводы для всех сообщений с ошибками и статистики;

### Анарихя "Classic".
— Удалён потенциальный эвент "данжы";

## 1.5 (03.04.2025)

### Анархия "Classic".
— Обновлены [сиды](https://minecraft.fandom.com/wiki/Seeds) игровых карт;  
— Удалены все игровые карты дабы произошла перегенерация с новыми [сидами](https://minecraft.fandom.com/wiki/Seeds) (умные найдут применение одинаковым картам на анархиях);  

## 1.4 (03.04.2025)

### Анархия "Classic".
— Добавлена [коллизия](https://www.mcpk.wiki/wiki/Collisions) предметов;  
— Скорректированы лимиты на появление мобов;  
— Добавлено авто-сохранение игровых карт;  
— Скорректировано кэширование карты спавна;  
— Исправлены критические уязвимости;  
— Обновлены встроенные в ядро сообщения;  
— Отключено сохранение ненужных кэш файлов (оптимизация);  

### Анархия "PvP".
— Обновлены зависимости (взаимодействие с аукционом);  
— Обновлены пакетные обработчики (фиксы на версии 1.20 и выше);  

## 1.3 (02.04.2025)

### Боты.
— Добавлены фотографии ко всем ботам в Telegram;  
— Добавлены описания и информация о ботах в Telegram;  

### Таблист.
— Исправлена задержка на появление таблиста на версии 1.20;

## 1.2 (02.04.2025)

### Версии.
— Скорректировали взаимодействие с игровыми версиями на всех режимах дабы была поддержка исключительно 1.16.5 — 1.20.5;  
— Изменили названия во всех социальных сетях на актуальные версии игры;  
— Исправлена ошибка поддержки пакетных данных версии 1.20 между версией 1.16 (структуры т.е. блоки, предметы и др. от версии 1.20 корректно отображаются на версии 1.16);  

### Авторизация.
— Количество аккаунтов доступных для регистрации увеличено с 2 до 3;  
— Теперь при регистрации вводить повторно пароль не нужно;  
— Изменены ссылки на техническую поддержку;  
— Во всех гайдах команды сокращены до их коротких версий (например, `/register` на `/reg`);  

### Меню.
— Исправлена ошибка поддержки материалов на версии 1.20;  

## 1.1 (02.04.2025)

### Техническая поддержка.
— Начала своё существование через [бота в ТГ](https://t.me/agetimehelpbot);

### Пинг.
— Обрезали попытки проверки информации о сервере с подозрительных сетей (теперь они получают интересное сообщение в ответ);  
— Оптимизировали код обработки данных пинга из лаунчера, теперь быстрее отображается информация о сервере;

## [1.0](https://t.me/agetime_dev/70) (30.03.2025)

### Бот привязки.
— Добавлена функция привязки аккаунта по [ТГ боту](https://t.me/agetimebot);  
— Отвязки аккаунтов отключены и удалены (пропала кнопка и функция в боте, если в клавиатуре она ещё осталась, то напиши боту команду "!клавиатура");  
— В боте удалены статусы 2FA (Подтверждения входа), по умолчанию 2FA у всех включена и отключить это нельзя (привязали = всегда подтверждаем вход);  
— Теперь бот на неизвестные сообщения отвечает навигацией по привязке.  