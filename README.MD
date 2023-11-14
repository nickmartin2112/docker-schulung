1. Aufgabe

In diesen Dockerfile wollen wir das Hello World aus die index.php 
Datei hinein kopieren um es später anzuzeigen.

Beachte Folgendes:
 - Der Image Name soll heissen: helloworld:1.0.0
- Frage hat das Image mehr als 3 Layer? [ANTWORT]
- Starte das image als Containername meinerstercontainer auf port 9112. Achte daruf das 
der Container im detach läuft.

Hilfe:

copy - kopiert Datein vom Localhost in das jeweilige Verzeichnis

docker build [Options] . (-t IMAGENAME)

    -f Folder dockerfile 

docker run [OPTIONS] IMAGENAME

    -p [127.0.0.1:[öffentlicher Port]:[Zielport im docker]]

    -d  Container laufen im Hintergrund



