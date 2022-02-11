# TVR
Группа 910902
=====================
***
Developers:
=====================

Косарева Екатерина
=====================
Забавская Валерия
=====================
***
### Глоссарий

***
Nugget –  компьютерная игра в жанре 2D-платформера.

Платформер  — жанр компьютерных игр, в которых основу игрового процесса составляют прыжки по платформам, лазанье по лестницам, сбор предметов, необходимых для победы над врагами или завершения уровня.

Runner и Endless Runner — жанры игр, в центре внимания которых герой-бегун. Практически всегда персонаж бежит автоматически и от игрока требуется лишь корректировать его траекторию движения, вовремя совершать прыжки и уклоняться от препятствий.

Лаунчер -это программная оболочка, основной задачей которой является удобный запуск приложений.

fps - (frame per second) кол-во кадров секунду.
***
### 1.Введение 
***

### 1.1 Назначение 


В рамках данной спецификации требований программного обеспечения описывается назначение и область действия данного приложения. Также цель документа состоит в анализе и в получении глубокого понимания функционала игры Nugget, сборке всех различных идей, определении системы, ее требований по отношению к потребителям. Также будут изложены концепции, которые будут разработаны позже, и будут документрироваться идеи, которые будут рассмотрены, но могут быть отброшены по мере развития продукта.

### 1.2 Область действия проекта

Данный проект является 2D игрой, идея которой заключается в преодолении препятствий посредством прыжком и уклонов.  Данная игра рекомендутся для аудитории старше 12 лет.

### 1.3 Аналоги разрабатываемого проекта

* Geometry Dash — компьютерная игра в жанре 2D-платформера, выпущенная изначально для мобильных устройств на iOS/Android, позже и для настольных компьютеров.  Игровой процесс заключается в прохождении уровня со множеством препятствий под ритмичную музыку.
* Dinosaur Game, также известная как T-Rex Game или Dino Runner, носившая первоначальное кодовое название Project Bolan — встроенная браузерная игра в браузере Google Chrome.
***
### 2 Общее описание

***
### 2.1 Функционал продукта

Данная игра позволяет персонажу проходить препятствия перепрыгивая их или уклоняясь от объектов.

### 2.2 Классификация пользователей

Игроки, которым нравятся жанр 2D-платформера.
Игроки, которые хотят попробовать для себя новый жанр.

### 2.3 Операционная среда

Операционная система: семейство Microsoft Windows.

### 2.4 Инструментарий разработки

Игровой движок: Unity 2020.3;
Используемый язык программирования: C#.

### 2.5 Предполагаемые зависимости

Приложение будет работать при наличии DirectX 11 и видеокарты с поддержкой Shader Model 4.0 и выше.
***
### 3.Требования к интерфейсу
***

### 3.1 Пользовательский интерфейс
![photo](https://user-images.githubusercontent.com/98969829/153667211-37154cb4-c160-4f89-bd91-52d777887e24.png)

* Картинка 1 - Главное меню игры;
* Картинка 2 - Игровой процесс;
* Картинка 3 - Интерфейс магазина, где можно купить скины;
* Картинка 4 - Настройки управления.
***
### 4.Функциональные требования
***
* Начать игру;
* Просмотр управления;
* Выйти из игры;
* Покупка новых скинов.
