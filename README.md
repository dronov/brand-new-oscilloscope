# brand-new-oscilloscope

Привет! 

Это — начальная репка готовящегося опенсорсного проекта под кодовым названием "осциллограф".

### Идея

Разработать опенсорсное (во всех смыслах и ипостасях) устройство (осциллограф) таким образом, чтобы заинтересованный человек мог в *три шага* 
* Купить комплектующие 
* Собрать без паяльника устройство
* Записать образ системы на sd-карту

получить работащий девайс (осциллограф) + *несколько прикольных плюшек*.

### Как мы это будем делать

Задачи разработки делятся на шесть основных зон (и файлов в репозитории). Одна общая зона и пять более специализированных. Пока обсуждение будем вести здесь. Почему не вики? Потому что в репке видно кто, когда и что менял в файле идей, плюс тут есть удобные комменты для обсуждений. Кроме того, есть седьмой файлик, где всем нужно накидывать идеи. Читаем, комментим, решаем что будем делать, а что нет. 

* 00-common.md общее описание осциллографа
* 01-hardware.md задачи разработки железа
* 02-peripheral.md разработанный обвес нужно представить в виде системного api linux
* 03-os.md задачи сборки, настройки ос и раздачи прошивок
* 04-software.md задачи непосредственного софта 
* 05-backend.md задачи бэкенда
