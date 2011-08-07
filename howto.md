#First step
Der erste Schritt zum wirklichen Consolenguru machst du, indem du eine Konsole
öffnest. Ein Weg um eine Konsole zu öffenen, ist die Tastenkombination `Alt+F2`.
Es öffnet sich ein Fenster in dem du beliebige Programme starten kannst. Hier
gibst du `zsh` um eine Z-Shell zu starten.

Informationen zur Z-Shell gibt es unter ...

#Das Dateisystem
##ls - List directory contents
Der Befehl `ls` zeigt dir den Inhalt des akutellen Verzeichnis an. Ls öffnet dir
die Augen ;)

Mit dem Öffnen deiner Konsole solltest du in deinem `Home`-Verzeichnis gelandet
sein. Guck dir jetzt den Inhalt deines `Home`-Verzechnis mit `ls` an. Irgendwas
interessantes gefunden? Manchmal verstechen sich die interessanten Datein auch.
`ls -a` zeigt dir versteckte Dateien an. Kannst du die versteckte Datei
`.bashrc` finden? Wie groß ist die wohl? `ls -l .bashrc` zeigt dir Informationen
zur Datei an. `ls -l` zeigt dir Informationen zu einem ganzen Ordner an. Du
kannst die Optionen auch kombinieren, z.B. `ls -la`. Eine Idee was passiert?

##cd - change directory
Mit dem `cd` Befehl kannst du dich in der Verzeichnisstruktur bewegen. In Linux
gibt es ein sogenanntes Wurzelverzeichnis. Das Wurzelverzeichnis ist der oberste
Punkt in der Verzeichnisstruktur. Mit `cd /` können wir ins Wurzelverzeichnis
aka root directory wechseln. Im root directory liegen einige wichtige
Systemordner, die wir uns später angucken können. Mit `cd ~` wechseln wir wieder
in unser Home-Directory. Die Tilde `~` steht für unser "Home" directory. Es geht
aber auch noch schneller. Mit `cd` kommst du von jedem Ordner zurück in dein
Home.

##mkdir - make directories
Als nächstes wollen wir uns einen Ordner mit ein paar Dateien anlegen. Dazu
benutzen wir den `mkdir` Befehl. Geh in dein Home-Verzeichnis und leg ein Ordner
mit dem Name "foo" an. `mkdir foo` sollte den Ordner anlegen. Jetzt wechsel in
den Ordner und versuch einen Datei anzulegen. 

##touch - 
Dateien lassen sich z.B. mit
`touch` anlegen. `touch bar` legt eine neue Datei `bar` ein. Mit `ls` kannst du
überprüfen, ob die Datei wirklich angelegt wurde.

##rm - remove files or directories
Meine Oma sagte immer: Lerne Ordnung, liebe sie, sie erspart dir Zeit und Müh.
Diese Weisheit kommt zwar aus der Vor-Konsolen-Zeit, aber trifft trotzdem auf
sie zu. Mit dem `rm` Befehl lässt sich wunderbar aufräumen. Wenn du immer noch
im Ordner foo bist, kannst du mit `rm bar` die "bar"-Datei löschen. Wenn du
wieder in dein Home-Verzeichniss wechselst mit `cd ..`, kannst du auch den
Ordner foo löschen. Versuchs mal mit `rm foo`... Geht nich? Verzeichnisse löscht
man mit `rm -r`. Funktionierts? Manchmal macht Aufräumen auch agressiv. Mancher
Müll will einfach nicht weg. Da muss Mensch dann Gewalt anwenden. `rm -f`
entfernt auch hartneckigen Schmutz, aber vorsichtig. manchmal macht es Sinn,
dass sich Dateien nicht normal entfernen lassen.





#Bla
##man - Manual pages
Wenn man/frau nicht mehr weiter weiẞ, hilft der Befehl `man` weiter. Gib einfach
`man <Befehlsname>` ein (die Spitzenklammern <> bezeichnen Platzhalter, d.h.
alles, was in solchen steht, ist durch einen gültigen Befehls-, Datei-,
etc.-namen zu ersetzen), und dann bekommst du eine ausführliche (oder weniger
ausführliche) Erklärung für die Funktionsweise, mögliche Optionen und Parameter
des Befehls.

Versuch `man ls` anzugeben und guck was passiert. Erkennst du die Optionen, die
wir oben genutzt haben, wieder? Lies ein anderes Manual page, just for fun.

##who am I
Zeigt dir an, wie dein Username lautet, auf welchen Terminal du angemeldet bist,
welchen Tag und welche Uhrzeit wir grad haben. Nützlich^^

##who
wenn du nur `who` eingibst, dann zeigt dir Linux an, welche Benutzer aud dem
System eingeloggt sind.
Ausprobieren!

##cal
`cal` ist ein nützliches Kalenderprogramm für die Shell. Wenn du nur `cal`
eingibst, dann zeigt sie dir den aktuellen Monat an. Optionell kannst du `cal
[<month>] [<year>]` angeben, was einen Kalender für die ausgewählten Monat
und/oder Jahr herzaubert. (Die eckigen Klammern [] bezeichnen optionale
Angaben).
Aufgabe: Lass dir den May 1988 anzeigen.

##date
Damit kann man sich nach der aktuellen Systemzeit erkundigen oder diese
einstellen. Gib `date` in deine Konsole ein. Zum weiteren schick-schnack kannst
du, richtig, die Manual page von date lesen...

##IPython

`IPython` ist eine verbesserte Shell für Python. Unter anderem ist sie bunt und
bietet nützliche Features wie z.B. auto-completion. `IPython` gibt es
[hier](http://ipython.org). Mit `aptitude` geht es auch:

    aptitude install ipython

##Oh-my-zsh

`Oh-my-zsh` ist eine Sammlung von verdammt nützlichne Erweiterung für die
`Z-Shell`. Brauchst du einfach. Findest du
[hier](https://github.com/robbyrussell/oh-my-zsh).

##Gmate

`Gmate` ist eine Sammlung von Plugins und Verbesserungen für `Gedit`. Mehr
Information auf [GitHub](https://github.com/gmate/gmate.git).

##Janus

`Janus` ist eine mächtige Sammlung von `vim`-Plugins. Siehe
[https://github.com/carlhuda/janus](http://github.com/carlhuda/janus)
