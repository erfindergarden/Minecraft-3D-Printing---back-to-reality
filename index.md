# Minecraft 3D Printing - Back to Reality 


by [erfindergarden](htto://www.erfindergarden.de) [@andreaskopp
](http://www.twitter.com/andreaskopp)

für [Junior Lab](juniorlab.de) [@Fablab Berlin](https://fablab.berlin/)


Was du brauchst: 


* mineways software
* WorldEdit Plugin
* einen mojang account
* einen 3D Drucker




## 1. Installiere Mineways

Installiere die Software [Mineways](http://www.realtimerendering.com/erich/minecraft/public/mineways/). Es gibt sowohl eine Mac als auch eine Windows Version. 


## 2. Installiere WorldEdit

### Wenn du einen Server hast

Aktiviere das WorldEdit plugin auf deinem Server. 
Gehe auf deinen FTP Server und in den Ornder plugins/WorldEdit/

Erstelle einen Ordner schematics auf deinem FTP Server. 

Wichtig! Der Ordner muss klein geschrieben werden. 


### Wenn du local Singleplayer spielst

Folge diesem [Video Tutorial.](https://www.youtube.com/watch?v=osVus2Bq97c).


Erstelle eine Folder schematics im order .minecraft/config/worldedit



## 3.1 Baue etwas in deiner Welt 

Baue etwas in deiner Welt. Am besten funktioniert eine FLAT world ohne creeper.

Achte darauf, dass keine Büsche neben deinem Objekt wachsen, das du exportieren willst.  

## 3.2 Importiere ein Object aus Tinkercad 

Du kannst auch etwas in [tinkercad](ps://www.tinkercad.com) bauen und klicke dann oben Recht auf "Download for Minecraft."

Du kannst sogar schon in Tinkercad mit Farben deine Blöcke in Minecraft definieren. Hier findest du die [komplette Liste](http://blog.tinkercad.com/2016/03/10/5707/).

RED = TNT ; Block of Redstone ; Redstone Ore

ORANGE = Glowstone ; Pumpkins ; Lava

YELLOW= Sandstone ; Sponge ; Block of Gold

GREEN= Slime Block ; Block of Emerald ; Leaves

BLUE/TEAL= Prismarine ; Emerald Ore ; Diamond Ore

BLUE/AQUA= Block of Diamond ; Ice ; Lapis Lazuli Block

BLUE/NAVY= Packed Ice ; Water ; Lapis Lazuli Ore

PURPLE= Hardened Clay ; Wood Acacia/Dark Oak ; Netherrack

PINK= Beacon ; Stained Clay ; Bricks

BROWN= Wood ; Dirt ; Soul Sand

WHITE/GREY= Snow ; Block of Quartz ; Block of Iron

GREY/BLACK= Stone ; Bedrock ; Obsidian




### Server 

Kürze den Dateinamen und Uploade diese Datei in deinen vorher erstellten schematics Ordner auf deinem Server.

Mit diesem Command bekommst du dein schematic Object angezeigt.

```
//schem list
```

und mit diesem Command kannst dein schematic Object loaden. Der filename ist ohne .schematic.

```
//schem load <filename>

```

mit ``` //paste ``` kannst du das Object dann einfügen. Sollte es dir nicht gefallen oder du die flaschen Blöcke in tinkercad ausgewählt haben kannst du mit ```//undo``` das Objekt wieder verschwinden lassen. 


Hier die ganze [Command List](http://wiki.sk89q.com/wiki/WorldEdit/Reference) von WorldEdit.


## local Single Player

Die gleichen Commands funktionieren auch.

http://minecraft.de/showthread.php?55819-How-To-Schematics-benutzen-erstellen


## 3.3 Baue dein Objekt mit WorldEdit

Du kannst auch dein Objekt auch mit der [World Edit](http://khroki.github.io/MCEdit-Unified/) Sofware bauen oder direkt mit Kommandos. [Hier](http://wiki.sk89q.com/wiki/WorldEdit/Generation#Pyramids) findest du ein paar Beispiel Kommandos. 

Wie z.B. eine Pyramide mit dem Radius 5 aus Steinen

```
//pyramid stone 5
```

Oder Einer Sphere mit dem Radius 5


```
//sphere stone 5
```

## 4. Finde deine Welt


### Server

Suche den Backup Folder deines Server und lade den ganzen Folder deiner Welt herunter in der du dein Objekt gebaut hast. Öffne die level.dat Datei darin mit mineways.



### Local Singleplayer

Öffne Mineways und suche den Ordner wo deine Minecraft Welten abgespeichert sind. Lasse dir die auch die schreibgeschützten Dateien anzeigen.

Für Mac: 

```
Z:/Benutzer/<username>/Library/Application Support/minecraft/saves/ 

```

Für Window: 

```
%APPDATA%\.minecraft\saves\

```

Für Linux:

```
~/.minecraft/saves
```


### Pocket/ Pi Edition

Kopiere die Welten von deinem Pi auf einen Stick oder von deinem i-phone/i-pad mit i-explorer und einem i-phone Kabel auf deinen Computer.

Öffne WorldEdit und folge dieser [Anleitung](http://www.realtimerendering.com/erich/minecraft/public/mineways/mineways.html#mcpe).


## 4. Exportiere dein Objekt

Selektiere dein Objekt. Das ganze Objekt sollte rosa sein. Exportiere es als stl Datei.


## 5. Öffne die Datei in Cura

Öffne die stl Datei in Cura oder deinem Slicer Deiner Wahl.
Skaliere dein Objekt für die gewünschte Größe. Hier kann dir das nächste mal jemand aus dem Fablab helfen. Wenn du noch gar keine Erfahrung mit 3D Drucker hast kannst du die stl Datei auch an shapeways schicken oder an ein 3dhub und die drucken dein Minecraft Objekt dann für dich.

