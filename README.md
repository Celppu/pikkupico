# pikkupico
Celp tech industries first microcontroller

First attempt of making smallest possible esp32 WITH lipo battery overdischarge protection. I didn't find any on the market so had to do one myself. Overdischarge protection kicks in at around 2.9v and locks out until charged over 3v. Usefull even if software sleep fails.

Uses esp32-c3 that uses very little power, DW07D random lipo protection ic with only chinese datasheet and ch340E serial converter. So far learned that
ch340E cannot put micro to flash mode and that DW07D thinks that disconnected battery means empty and so it locks out until charged.

TODO next verion remember strapping pins and remove usb flash button. Currently not out of the box working
![pikkupico](https://user-images.githubusercontent.com/42336725/171724334-3937b3fd-16ed-49eb-9333-6a1dabd063cc.jpeg)

Project requiring higly customized tech.
![valoi](https://user-images.githubusercontent.com/42336725/182961554-3e0e72d5-b14b-44f1-8631-25fdf2b9339b.gif)

