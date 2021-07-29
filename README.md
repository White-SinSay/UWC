<h2>Данный проект был расзработан совместно с Виталием с Youtube канала  <a href="https://www.youtube.com/channel/UCzI016x7MItBtQCJiSWI7yA" target="_blank">Уголок технаря</a></h2>
<br>
Была разработана основная плата, в которую можно вставить до 5 модулей (о них расскажу ниже)
Основная плата может питься от разных источников питания, от 5в, от 7 до 20в (через модуль DC-DC перобразователя) а также от 220в
Фото основной платы, PCB схема и 3D вид ниже
Список компонентов и принципиальные схемы будут выложены позже
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/main.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/main.png" width="180" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/main_pcb.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/main_pcb.png" width="180" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/main_3d.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/main_3d.png" width="180" height="180"></a>
<br>
<h2>А теперь о модулях</h2>
<h3>1- Модуль реле с сухими контактами (до 10А)</h3>
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/relay.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/relay.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/relay_pcb.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/relay_pcb.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/relay_3d.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/relay_3d.png" width="120" height="180"></a>
<br>
<h3>2- Модуль c твердотельным реле (до 2А)</h3>
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/relay2.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/relay2.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/relay2_pcb.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/relay2_pcb.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/relay2_3d.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/relay2_3d.png" width="120" height="180"></a>
<h3>3- Модуль c мосфетом</h3>
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/mosfet.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/mosfet.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/mosfet_pcb.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/mosfet_pcb.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/mosfet_3d.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/mosfet_3d.png" width="120" height="180"></a>
<h3>4- Модуль для подключение датчиков и сенсоров</h3>
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor_pcb.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor_pcb.png" width="90" height="180"></a>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor_3d.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor_3d.png" width="120" height="180"></a>
<br>
А вот тут есть что немного пояснить<br>
а) Подключение возможно только одного датчика или сенсора. Подключить 2 или более нельзя (за исключением некоторых, таких как ds18b20)<br>
б) на данном модуле есть есть 3 вход-выхода<br>
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-123.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-123.png" width="90" height="180"></a>
<br>
Разберем первый вход
<br>
Если датчик питаеться от 3в то необходимо установить перемычку как на рисунке (одновременно перемычку на 3в и 5в устанавливать нельзя)<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-1-3v.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-1-3v.png" width="90" height="180"></a>
<br>
Если датчик питаеться от 5в то необходимо установить перемычку как на рисунке (одновременно перемычку на 3в и 5в устанавливать нельзя)<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-1-5v.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-1-5v.png" width="90" height="180"></a>
<br>
Если для датчика необходима подтяжка к + питания, то установити перемычку как на рисунке ниже<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-1-pullup.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-1-pullup.png" width="90" height="180"></a>
<br>
Разберем второй вход
<br>
К данному входу можно подключать кнопки и герконы. Если требуеться PullDOWN то установите перемычки как на рисунке<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-2-pulldown.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-2-pulldown.png" width="90" height="180"></a>
<br>
К данному входу можно подключать кнопки и герконы. Если требуеться PullUP то установите перемычки как на рисунке<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-2-pullup.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-2-pullup.png" width="90" height="180"></a>
<br>
Разберем третий вход.
<br>
Тут все просто. Для его использования необходимо демонтировать все перемычки. И установить только одну, как на рисунке<br>
<br>
<a href="https://github.com/White-SinSay/UWC/blob/main/images/sensor-3.png"><img src="https://github.com/White-SinSay/UWC/blob/main/images/sensor-3.png" width="90" height="180"></a>
