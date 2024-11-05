# lesson45-46
Болкарева Анна

#45

1-топологии - основные структуры сетей с разными схемами соединения

2-Шина - это линия связи, которую несколько устройств используют для обмена данными. В ней компьютеры подключены к одному кабелю с помощью специальных разъёмов. Чтобы сигнал не отражался от концов кабеля (и не шёл в обратную сторону), их закрывают заглушками (терминаторами). Так как существует всего одна линия связи, компьютеры передают данные по очереди. Сигнал, который идёт по шине, получают все компьютеры, но каждый из них обрабатывает только те данные, которые ему предназначены

Достоинства схемы «общая шина»:

-самая простая и дешёвая схема; 

-небольшой расход кабеля; 

-легко подключать новые рабочие станции; 

-при выходе на строя любого компьютера сеть продолжает работать.

Недостатки: 

-при разрыве кабеля или выходе из строя терминатора вся сеть не работает;

-низкий уровень безопасности (каждая рабочая станция имеет доступ ко всем данным, которые идут по сети);

-один канал связи на всех при увеличении числа компьютеров падает скорость передачи;

-возможны конфликты, когда две рабочие станции хотят передать данные одновременно); 

-сложно обнаруживать неисправности; 

-ограничение размера (не более 185 м, при большей длине нужны усилители сигнала)

  В схеме «звезда» есть центральное устройство, через которое идёт весь обмен данными. На практике чаще всего в центре находится коммутатор (его часто называют «свитч»). Коммутатор передает принятый пакет только адресату, а не всем компьютерам в сети. Многоуровневая схема «звезда» представляет собой иерархическую структуру (дерево). Она нередко применяется в крупных сетях, которые состоят из сотен компьютеров

Достоинства схемы «звезда»:

-при выходе из строя любой рабочей станции сеть остаётся работоспособной;

-высокий уровень безопасности (каждая рабочая станция получает только "свои данные", а не все, что передаются по сети);

-простой поиск неисправностей и обрывов (сразу ясно, с каким компьютером нет связи)

Недостатки: 

-большой расход кабеля, высокая стоимость; 

-при выходе из строя коммутатора вся сеть не работает; 

-количество рабочих станций ограничено количеством портов коммутатора

  В схеме «кольцо» каждый компьютер соединён с двумя соседними, причём от одного он только получает данные, а другому только передаёт. Таким образом, пакеты движутся по кольцу в одном направлении. Для повышения надёжности обыч но используют «двойное кольцо», в котором каждая линия связи дублируется. По второму кольцу данные могут передаваться в обратном направлении. Каждый компьютер участвует в передаче сигнала и усиливает его, поэтому размер сети может быть очень велик, ограничено лишь расстояние между соседними узлами (для оптоволоконных сетей до 2 км). 
  
  Достоинства схемы «кольцо»:
  
  -большой размер сети (до 20 км);
  
  -надёжная работа при большом потоке данных, конфликты практически невозможны; 
  
  -не нужно дополнительное оборудование (коммутаторы)
  
  Недостатки: 
  
  -для подключения нового узла нужно останавливать сеть;
  
  -низкая безопасность (все данные проходят через каждый компьютер);
  
  -сложность настройки и поиска неисправностей

3-В современных сетях кольцевая схема чаще всего используется в сочетании со «звездой»: компьютеры соединяются с коммутатором по схеме «звезда», а коммутаторы между собой объединяются в кольцо. поэтому я думаю, что этот вариант  подойдет и для школьной сети

#46

