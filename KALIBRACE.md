Kalibrace Z offsetu:

https://www.youtube.com/watch?v=GJiuji4d80M

G28 - home
G29 - bed leveling
G1 Z0 - absolute zero
M114 - kontrola os
G92x Z10 - přepsat Z na 10mm
pronter face a začít klesat až na papír
M114 - zobrazit a odečíst 10 - aktuální Z a použít jako negativní hodnotu
M851 Z-1.4
M500 - uložit vše do EEPROM
