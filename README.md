# Info System Free VIP
## 🎁 Give
🔔 *выдача вип по заданному времени<br>
🔔 выдача вип по заданным дням недели<br>
🔔 выдача вип по праздникам<br>
🔔 выдача вип при низком онлайне<br>
🔔 выдача вип когда на сервер зашел Гл. адм(будет в полной версии)<br>
🔔 меню выдачи вип игроку на карту<br>
🔔 активация вип на 1 раунд за деньги*

## ⏳ Install
1. *В исходнике раскоментировать необходимый способ выдачи*<br>
2. *Скомпилировать/залить/прописать(как обычно всё)*<br>
2.1. *Если используете способ выдачи по праздникам залить из архива файлик addons/amxmodx/configs/SFV/holidays.ini*<br>
3. *Перезапустить сервер или сменить карту*

## 🔧 Settings
//=======================ВЫБЕРИТЕ 1 ИЗ РЕЖИМОВ//============================\\ <br>
// Выбранный режим необходимо раскоментировать остальное настраивается кварами<br>
//#define VIP_BY_TIME // выдача вип по заданному времени <br>
//#define VIP_BY_DAY // выдача вип по заданным дням <br>
//#define VIP_BY_HOLIDAYS // выдача вип по праздникам<br>
//#define VIP_BY_ONLINE // выдача вип при низком онлайне<br>
//#define VIP_BY_ROOTADM // (данный способ будет в след обновлении)<br>
//#define VIP_MENU // меню выдачи вип игроку на карту<br>
//#define VIP_BAY_CMD // для активации вип на 1 раунд за деньги<br>
//===============================================================================\\ 

## 📰 Cvar's<br>Квары(прописывать в amxx.cfg)<br>
amx_vip1_start 0 // Время начала ночной вип <br>
amx_vip1_stop 8 // Время окончания ночной вип <br>
amx_vip2_day 3567 // перечислить дни для режима выдачи по дням<br>
// 1 - понедельник <br>
// 2 - вторник <br>
// 3 - среда <br>
// 4 - четверг <br>
// 5 - пятница <br>
// 6 - суббота <br>
// 7 - воскресенье <br>
amx_vip4_start 12 //Максимально кол-во игроков при котором все игроки вип <br>
amx_vip7_money 16000 // Цена випки на раун для режима покупки вип
