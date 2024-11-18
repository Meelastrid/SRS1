# Core Домен: спорт(большой теннис)
## Поддомены: 
Бот для поиска партнеров для игры, стриминг профессиональных матчей

### Сущности для бота: 
Игрок, Теннисный клуб
### Агрегаты: 
Матч

### Сущности для стриминга: 
Зритель, спортсмен, матч
### Агрегаты: 
Турнир

#### Объекты значений для бота: 
Для сущности игрок это:
* рейтинг с атрибутами уровень навыков и очки
* предпочтения с атребутами уровень партнера, время, локация
* контактные данные с атребутами номер телефона и ник в телеграм
* история матчей с атребутами количество побед и количество поражений
Для сущности теннисный клуб:
* адрес с атрибутами улица, номер дома
* условия с атрибутами цена, покрытие, количество кортов

#### Объекты значений для стриминга:
Для сущности зритель это: 
*  контактные данные с атребутами имя и электроная почта
* предпочтения с атребутом любимые игроки и врема матча
Для сущности спортсмен:
* личные данные с атребутами имя, страна, возраст
* рейтинг с атребутами очки, позиция в рейтинге
Для сущности матч:
* место проведения с атребутами название турнира, дата и время
* состав участников с атребутами имя первого и второго игрока

### Словарь терминов для бота.
Игрок - человек, который использует бота для поиска партнёров по теннису и участия в матчах.  
Рейтинг - показатель, описывающий уровень навыков игрока.  
Предпочтения описывают параметры, важные для игрока при поиске матчей.  
Контактные данные содержат контактные данные игрока.  
История матчей описывает предыдущие матчки игрока. 
Теннисный клуб - место, где проводятся теннисные матчи.  
Адрес - местоположение теннисного клуба.  
Условия - описание условий и характеристик клуба.  

### Словарь терминов для стриминга.
Зритель - человек, который просматривает трансляции теннисных матчей через стриминговую платформу.  
Контактные данные содержат информацию для описания и связи с пользователем.  
Предпочтения - личные вкусы зрителя относительно просмотра матчей.  
Личные данные - личная информация о спортсмене.  
Рейтинг представляет достижения и позицию игрока относительно других игроков.  
Место проведения - информация о дате и турнире матча.  
Состав участников - Информация об участниках матча.  
