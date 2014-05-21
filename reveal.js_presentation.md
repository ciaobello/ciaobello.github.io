Igit! Was ist denn dass?
========================

####*Git* ([ɡɪt], engl. Blödmann) ist eine freie Software zur verteilten Versionsverwaltung von Dateien, die ursprünglich für die Quellcode-Verwaltung des Linux-Kernels entwickelt wurde.  (wikipedia)


Das Prinzip einer Versionsverwaltung ist einfach.
Alles wird lokal gespeichert und mit einem Server wie Github sinchronisiert.

Über sogenante "pull requests" können sich andere Personen an der Programmierung beteiligen mit Ihren,
lokal gespeicherten Versionen der Daten.


Der beteiligende macht einen Vorschlag einer Code/Daten Änderung
und der Hauptprogrammierer/ProjektTeam kann diesen Vorschlag dann in seine Lokalen Daten aufnehmen oder verwerfen.

Nach den Änderungen, werden diese lokalen Daten wieder allen auf dem Server zur verfügung gestellt.


##### Demo um Git zu zeigen ohne installation: [Git Demo][1]

##### Download von Git | Terminal oder Commandozeile orientiert [Linux, Mac & Win][2]

[1]: http://try.github.io/levels/1/challenges/1
[2]: http://git-scm.com/downloads



Wie Starten?
------------

Terminal öffnen und folgende Befehle zur Personalisierung eingeben:

``` 

$ git config --global user.name "Gewünschter Name"

$ git config --global user.email "gewünschter.name@example.com"

```

"Gewünschter Name" kann einem Github/Bitbucket Nickname & email entsprechen


##### Pro kontra von Github & Bitbucket (english) [Externer Artikel][3]

[3]: http://www.infoworld.com/d/application-development/bitbucket-vs-github-which-project-host-has-the-most-227061?page=0,0



Damit wir nun Mit einem Projekt starten können geben wir folgendes im Terminal ein:

```
$ git init project
# Project ist freiwählbarer Name; Verzeichnis wird erstellt.
$ cd project
# Erstellen einer Datei
$ touch README.md
# Die Datei wurde erstellt, aber noch nicht permanent zugewiesen
$ git add README.md
# Siehe unten "Anleitung wie man den Markdown von Git verwendet" 
$ vi / nano README.md
# Die Daten welche ins Repo sollen. Wird rekursive hinzugefügt
$ git add VerzeichnisMitDaten
# Permanentes hinzufügen/entfernen zur Versionsverwaltung; 
# -m hängt eine Notiz an den Commit 
$ git commit -m "mein erster commit"

```
Wie man den Markdown von Git verwendet [Anleitung][5]
[5]: https://help.github.com/articles/github-flavored-markdown


Neugierig? Gerne selber versuchen?

In das entsprechende Verzeichnis wechseln wo das Repository gespiechert werden soll und eingeben:

```
$git clone https://github.com/ciaobello/start-git start-git

```

Weitere nützliche und einmalige Konfigurationen können dem [Git Handbuch][4] entnommen werden.

[4]: http://git-scm.com/book/en/Getting-Started-First-Time-Git-Setup
