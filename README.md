## Facial Recongnition via Composite and Photographic Portrait Comparison
НИР "**Распознавание человека сравнением натуралистическомго портретного изображения с композитрным портретом**"

Общая постановка задачи:  
>*Решается задача распознавания человека по его натуралистическому портретному изображению, при этом в базе данных известных человек имеются только их композитные портреты.*

Практический пример:  
>*На большинстве подъездов в городе установлены видеодомофоны. Мониторинг их видеопотока может быть полезен для поиска преступников. Часто в распоряжении правоохранительных органов отсутствует фотография разыскиваемого лица, однако может иметься фоторобот, составленный со слов потерпевших/свидетелей. Сопоставление полученных с камеры домофона портретных изображений с фотороботами может помочь в установлении местонахождения такого подозреваемого.* 
<p align="center">
<img src="https://user-images.githubusercontent.com/70561974/154902264-fd205b9e-e5e1-47b8-861e-3d985b82a391.png"/>
</p>

Допущения:  
- Во входном видеопотоке присутствуют только фронтальные изображения человеческого лица,
- Лица людей в видеопотокевидны полностью и не закрыты масками/шарфами/солнечными очками и т.д.

Приблизительный пайплайн:  
<p align="center">
<img src="https://user-images.githubusercontent.com/70561974/154902595-ad8ba7b4-1820-4ce8-85d7-10d36249dc89.png"/>
</p>
(Оранжевым выделен блок, над реализацией которого необходимо будет еще подумать, остальное можно реализовывать хоть сейчас, благо библиотеки для этого есть)