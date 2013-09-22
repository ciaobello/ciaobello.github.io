Igit! Was ist denn dass?
========================

####*Git* ([ɡɪt], engl. Blödmann) ist eine freie Software zur verteilten Versionsverwaltung von Dateien, die ursprünglich für die Quellcode-Verwaltung des Linux-Kernels entwickelt wurde.  (wikipedia)

Das Prinzip einer Versionsverwaltung ist einfach.
Alles wird lokal gespeichert und mit einem Server wie Github sinchronisiert.
Über sogenante "pull requests" können sich andere Personen an der Programmierung beteiligen mit Ihren,
lokal gespeicherten Versionen der Daten.

Der beteiligende macht einen Vorschlag einer Code/Daten Änderung
und der Hauptprogrammierer/ProjektTeam kann diesen Vorschlag dann in Seine Lokalen Daten aufnehmen oder verwerfen.

Nach den Änderungen, werden diese lokalen Daten wieder allen auf dem Server zur verfügung gestellt.

##### Demo um Git zu zeigen ohne installation: [Git Demo][1]

##### Download von Git | Terminal oder Commandozeile orientiert [Linux, Mac & Win][2]


Wie Starten?
------------

Terminal öffnen und folgende Befehle zur Personalisierung eingeben:

``` 

$ git config --global user.name "Gewünschter Name"

$ git config --global user.email "gewünschter.name@example.com"

```


"Gewünschter Name" kann einem Github/Bitbucket Nickname & email entsprechen

[Pro kontra von Github & Bitbucket (english)][3]


Damit wir nun Mit einem Projekt starten können geben wir folgendes im Terminal ein:

```

$ git init project  (project ist freiwählbarer Name für welchen eine Verzeichnis erstellt wird)
$ cd project

$ touch README.md (erstellen einer Datei)
$ git add README.md (die Datei wurde erstellt ist aber noch nicht permanent der Versionsverwaltung zugewiesen)
$ git commit -m"mein erster commit" (permanentes hinzufügen/entfernen zur Versionsverwaltung; 
                                     -m hängt eine Notiz an den Commit) 

```

Neugierig gerne selber versuchen?

In das entsprechende Verzeichnis wechseln wo das Repository gespiechert werden soll und eingeben:

```

$git clone https://github.com/ciaobello/start-git start-git

```

Weitere nützliche und einmalige Konfigurationen können dem [Git Handbuch][4] entnommen werden.


[1]: http://try.github.io/levels/1/challenges/1
[2]: http://git-scm.com/downloads
[3]: http://www.infoworld.com/d/application-development/bitbucket-vs-github-which-project-host-has-the-most-227061?page=0,0
[4]: http://git-scm.com/book/en/Getting-Started-First-Time-Git-Setup



