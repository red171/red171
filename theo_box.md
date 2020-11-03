> Der nachfolgende Brief wurde am Dienstag, 03.11.2020 gegen 18 Uhr veröffentlicht und verfolgt kein anderes Ziel als aufzuzeigen was `theo_box` für ein [Scharlatan](https://de.wikipedia.org/wiki/Scharlatan) und [Heuchler](https://de.wikipedia.org/wiki/Heuchelei) ist!

# Lang lebe appleJuice.. oh wait..

Liebe appleJuice Community,

der ein oder andere hat die letzten Tage vielleicht mitbekommen, dass es im Netzwerk veränderungen gab.

applejuicenet.DE war offline, applejuicenet.CC kam als Ersatz, applejuicenet.DE ist plötzlich wieder da, alles komisch gerade, oder?

Ich bin **richtig** angepisst, ich bin enttäuscht, ich bin sauer! :rage:

Was ist also passiert?


## Die Kurzfassung

`theo_box` hat versucht, die Serverbetreiber zu erpressen, in dem er `2.000€` für die beiden http://applejuicenet.DE (.ORG) Domains haben wollte, andernfalls würde das Netzwerk sterben :boom: 

Wir, die Serverbetreibern waren entsetzt und haben uns das nicht gefallen lassen :scream: 

Ich, red171, habe den appleJuice Core ohne Zustimmung durch `theo_box` angepasst und somit "Rechte" verletzt :pencil: 

Statt dass mich `theo_box` ordentlich abmahnt, droht er damit, meinem Arbeitgeber zu informieren, was ich "so treibe". :ghost: 

Ich habe aufgrund dieser Nötigung meinen Arbeitgeber proaktiv informiert um `theo_box` die Angriffsfläche zu nehmen. :skull: 

> Update vom `17.11.2020` gibt es [hier](https://github.com/red171/red171/blob/master/Putsch.md). :heavy_exclamation_mark:


## Die Langfassung

Der Inhaber `theo_box` der Domains http://applejuicenet.DE hat uns, die Servertreiber, in einem privaten Channel folgende Nachricht zukommen lassen:

Zitat von Sonntag, 25.10.2020 17:31 Uhr

```
theo_box:
@an alle Serverbetreiber!
Ich bin nun schon seit der Geburt von AJ dabei und ihr könnt mir glauben, dass mir diese Entscheidung nicht leicht gefallen ist.
Doch nach langer, reiflicher Überlegung und auch in Rückblick auf die letzten (jüngsten) Ereignisse bin ich zu dem Entschluss gekommen mich von "appleJuice" zu trennen und zurückzuziehen.

Es gibt jetzt zwei Möglichkeiten bzw. Szenarien:
- Es findet sich jemand, der bereit ist "applejuicenet.de/org" weiterzuführen und die Domain von mir übernimmt (heißt die Domain von mir abkauft für 2.000,00 Euro).
- Ich schalte die Domain ab und verkaufe diese auf dem Domain-Marktplatz. Was auch heißt, dass damit die AJ-Server ihre Konnektivität verlieren und das Netz damit sich selbst beendet.

Bei der ersten Variante bin ich bereit meinen AJ-Server (theobox.applejuicenet.de) erst einmal weiterlaufen zu lassen, da er ja kostengünstig ist mit 1 Euro. Des weiteren übergebe ich den MoneyPool von zurzeit 150 Euro an den neuen Betreiber. Damit kann man AJ auch erst einmal eine Weile über Wasser halten.
Diskutiert die Sache hier im Serverkreis mal in Ruhe und betrachtet die Angelegenheit als Intern. Bitte die Diskussion nicht in die Öffentlichkeit bringen.
```


Meine unmittelbare persönliche Reaktion dazu war folgende:

```
red171:
Spannend, war aber irgendwie zu erwarten. Du solltest aber wenn dann die Serverbetreiber über alles Informieren, was vorgefallen ist. Weil die Aussage "der jüngsten Ereignisse" ist super intransparant... Aber das ist ja leider Grundsätzlich nichts neues bei euch "alten Hasen".. Statt miteinander und mal offen zu reden, gibts überall nur heimlichtuerei und so wenig Infos wie nur irgend möglich.

Das ganze auch nicht öffentlich zu machen, ist mMn auch eher unglücklich - wie sollen sonst die von dir verlangten 2k zusammen kommen? Wobei die Summe an sich schon echt frech ist, dafür das NUR die Domains raus rückst. Außerdem zeigt es mir, wie bereits von mir seit langem vermutet, das es gar keine Master Server gibt. Sonst müssten die ja Teil des Angebotes sein.
Da kauf ich lieber ne neue domain und pass alle GUI, den Core und Server kurz an, das die auf die neue Domain zugreifen..
Das Netzwerk scheint ja dadurch Autark zu sein!

ich jedenfalls blätter keine 2k hin, vor allem nicht "nur" für Domains.. mehr gibts ja in dem Deal scheinbar nicht.

Der Moneypool ist irgendwie genauso ein Witz, für Domains und Serverkosten soviel Kohle zu verlangen.
Die aktuellen beiden Domains kosten 20€ im Jahr (.de 5€, .org 15€), ein Webspace der den dynamischen serverlist.php XML kram abfängt 1-2€ im Monat. Der Rest ist statischer kram, wie man an https://applejuicenet.github.io/ ja sehr gut erkennt.

Also alles im allem finde ich das sehr überzogen, dafür das du zum zweiten mal dem ganzen ein Ende machen willst.

PS: die Server beenden sich nicht selbst, nur weil die Domain nicht erreichbar ist ;)

Du machst gerade - leider - muhviestar 1zu1 nach, finde ich eher schade, dafür das dir angeblich soviel am AJ Netz liegt.
```


Es folgten noch weitere Aussage der anderen Serverbetreiber, einiges an Entsetzen und Unmissverständnis.

Zugegeben, meine Antwort war auch nicht die Beste, in Anbetracht der Tatsache das es sich hier aber am Ende um eine Erpressung handelte, sicherlich irgendwie verständlich: "geb mir 2k oder das Netzwerk schaltet sich ab"...

Durch meine Antwort hat `theo_box` sich scheinbar so angegriffen gefühlt, das er noch am gleichen Abend, nur Stunden später die beiden Domains applejuicenet.DE und applejuicenet.ORG offline genomme und auch alle DNS Einträge entfernt hat, so das  die drei von mir betriebenen Knast* Server und viele andere Services nicht mehr funktionierten!
(Gedanke: Ich nehme an, das `theo_box` u.a. darauf spekulierte, das ich die Domains übernehme, da ich mich in den letzten 18 Monaten so engagiert habe.. aber wer weis das schon).


Dazu muss man wissen:
Das AJ Netzwerk ist in gar keinem Fall auf die Domains angewiesen, das ist nur ein nettes Gimmik, damit sich der Core dort eine stets aktuelle Serverliste holen kann. Außerdem melden sich die Server an der Serverliste alle 5 Minunte mit einem "hallo, ich existiere, nehm mich in die Liste auf".
Fallen die Domains weg, funktioniert das Netzwerk weiter (wie wir ja von Sonntag Abend an gut sehen konnten..).
Das Netzwerk funktioniert Autark, sogar ohne Server. Diese dienen lediglich der Vermittlung! Selbst die Clients funktionieren ohne Server, wenn man sich " ajfsp links mit source" sendet.


Parallel diskutierten wir Serverbetreibern einem weiteren privaten Chat Raum (ohne `theo_box`) und haben nach einer Lösung gesucht, wie wir das AJ Netzwerk am leben erhalten können.
Kurzentschlossen wurde die Domain http://appplejuicenet.CC registriert und auf die bereits vorhandene Github Page gelenkt (was bis dahin eine Spielwiese von mir).
Die drei Knast*Server wurden fix von mir umkonfiguriert und alles lief wieder wie gewohnt.

Einen Tag später, Montag, mein Freier Tag, entschied ich mich dazu, die JavaGUI und die phpGUI für die Serverliste auf http://applejuicenet.CC umzuschwenken.
Eine im nachhinein unkluge Entscheidung von mir war es, den appleJuice Core ebenfalls anzupassen, und auf die .CC umzuschwenken, damit der Core sich dort weiterhin aktuelle Server holen kann.

`theo_box` schrieb mir bereits kurz vor dieser unklugen Entscheidung per E-Mail, das die "Rechte" der Software "appleJuice" bei ihm liegen würde, und ich sein Einverständnis benötige. Ich ignorierte das, bzw. vertraute nicht darauf, dass dem so ist, da `theo_box` generell viele Unwahrheiten verbreitet und ich mir nicht sicher sein konnte, das dem wirklich so ist.
Zu den Unwahrheiten gehört u.a:
- das die Server ohne die Domains nicht funktionieren
- das er 25 Clienten gesperrt hätte (was schon Ewig in den GUI News steht) (Auf der Website stand irgendwo sogar 50)
- das es einen "Master" Server mit "Kill Switch" im AJ Netzwerk gibt
- das neue Server manuell freigeschaltet werden müssen
- das am Core weiter entwickelt wird
- das man unbedingt das Oracle JRE nehmen müsse
- usw...

Es gab noch die ein oder andere kurze Mail, dann war aber erst mal bis Sonntag, 01.11.2020 Ruhe; um 13.56 Uhr trudelte eine neue Mail von `theo_box` ein.


Statt mich ordentlich abzumahnen, das ich gegen das Lizenzrecht verstoße und die "Rechte" verletzt habe, wird die applejuicenet.DE Domain wieder Online geschaltet, mit dem Hinweis das die Veränderung illegal war.
Das schlimmste aber ist, Obendrauf zu der eingangs erwähnten Erpressung "2k oder Netzwerk offline", das `theo_box` mich persönlich bedroht/nötigt, mit Aussagen wie dieser:

```
theo_box:
... Ich hatte mir ja frühzeitig immer Kopien gemacht von allen Dingen, die auf GitHub, Discord, WhatsApp und anderen Portalen gelaufen sind. Was du nach deinen Worten ja auch gemacht hast. Ich kann mir auch nicht vorstellen, dass dein Arbeitgeber begeistert ist, wenn er erfährt was du so treibst. Zumal du ja auch mittels Firmenhardware deine privaten Dinge erledigt hast.

Aber das nur am Rande. Hier geht es jetzt um "applejuice" und die Rechtsverletzung durch dich und andere. Diese Mail hat eine Anlage für dich. Wie du diese beurteilst überlasse ich dir. Du solltest aber alles in Ruhe abwägen und beurteilen ob sich das alles lohnt. Zumal du auch eine Verantwortung gegenüber deinen Nächsten hast. Vielleicht kann man sich ja doch dann wieder in die Augen schauen.
```
Die Anlage enthielt einen Screenshot von einer E-Mail zwischen `theo_box` und `muhviehstar`, in welcher `theo_box` erlaubt wird, den Core zu verändern (Echtheit unbekannt).

In einer weiteren Mail, eine paar Stunden später, auf meine Antwort per WhatsApp Sprachnachricht, kam Folgendes:

```
theo_box:
Aber zum wichtigsten Punkt deiner Nachricht erst einmal: "Ich habe und hatte nie die Absicht dich in Person zu erpressen. Du kannst denken wie du willst, aber das liegt nicht in meiner Natur. Ich gebe zu, ich habe ein kleines Problem mit-nachtragend sein-. Aber daran kann man arbeiten.
```
Es wurde ausgesprochen, es war und ist eine Drohung, ohne Wenn und Aber. Das Vertrauen ist für immer dahin und nicht wiederherstellbar. Es ist unter aller Sau gewesen sowas auch nur zu erwähnen!

```
theo_box:
Aber eins sehe ich jetzt wieder. Du suchst dir immer die Punkte raus, die dir anscheinend wichtig sind. Zum richtigen Nachdenken kommst du nicht, da bei dir sich ein bestimmtes Bild fest gefressen hat. Hast du einmal darüber nachgedacht, ob vielleicht dein eingeschlagener Weg auch falsch sein könnte?
```
Wer hat den Stunden später in einem Tobsucht Anfall beide Domains abgeschaltet? `theo_box` kommt einfach nie damit klar, wenn jemand an seinem Weltbild wackelt. Ja, das Bild ist fest gefressen: Um an der Stelle aber mal aus einem früheren Chat mit einer anderen Person zu zitieren:

```
anonym:
theo_box ist ein wenig selbstherrlich und trägt meiner Meinung nach eine Arroganz die nicht gut für das Netzwerk ist. 
```
Das spiegelt sich hier auch in nahezu jedem [Thread](http://www.apple-deluxe.cc/index.php?ct=803&searchID=68469) wider, wo `theo_box` antwort, immer von oben herab, immer weiß er es besser, und immer sind alle anderen seiner Meinung nach total unfähig.

Egal, mein Bild ist **tatsächlich** fest gefressen, weiter gehts..

```
theo_box:
Mir ist vollkommen klar das der Arbeitgeber seinen IT-Leuten bis zu einem gewissen Grad freie Hand gibt. Das kenne ich selbst, da auch ich mal bei einem großen Konzern gearbeitet habe (in Salzgitter/Peine). Aber, ich weiß auch wie nachtragend ein Konzern oder Unternehmen sein kann, wenn es um sein Renommee geht. Gerade wenn man dabei ist sich neue Standorte zu erschließen. Das bleibt ein ganzes Berufsleben an einem kleben. Und glaub mir, Unternehmer sind sehr gut vernetzt. Aber egal, ist nicht mein Anliegen. Ich wollte es dir nur mal vor Augen halten.
```
Gehts noch? Hier wird offensichtlich versucht mich zu deformieren und mir Angst zu machen!

Hier werden definitiv Grenzen von `theo_box` überschritten, die einfach gar nicht gehen, auch nicht hier in der "Community" oder gar in der "Szene"!
Es ist eine Sache, wenn ich in der Software eine Stelle im Code ohne Erlaubnis verändere, aber eine andere Sache, damit zu drohen, dass mein Arbeitgeber davon ja erfahren könnte, was ich privat "so treibe"!

Nötigung ist es deswegen, weil `theo_box` mich in die Ecke gedrängt hat, so das ich meinen Arbeitgeber proaktiv informiert habe, das ich privat an der Entwicklung einer legalen P2P Software beteiligt bin und dies auf dem mir zur Verfügung gestellten Firmengerät außerhalb meiner Arbeitszeit mache (man muss hier halt einfach mal differenzieren, das appleJuice selber legal ist).
Abgesehen davon, dass unsere Firmenhardware für die private Nutzung freigegeben ist, was `theo_box` aber auch immer wusste.

Ich weiß ehrlich gesagt nicht, was ich davon halten solle.. Jedes Mal, wenn ich darüber Nachdenke bin ich Sprachlos. Ich bin mitte 30 und lerne gerade erneut, wie sehr man sich in Menschen täuschen kann.

Erst werden wir Serverbetreiber erpresst und handeln nicht nach seinem Wunsch...
Dann wird so derbe unter der Gürtellinie auf privater Ebene daneben gehandelt, das mir keine andere Wahl blieb, als euch, die Community, vor dem großen Messias `theo_box` (der 2012 das AJ Netzwerk "gerettet" hat) zu WARNEN... Mir fehlen erneut die Worte...

Ich kann euch alle nur mit dem aller größten Nachdruck vor diesem Scharlatan warnen! Vertraut ihm in gar keinem Fall!

Nicht nur, dass er sich andauernd anmaßt, es in jedem Fall besser wissen zu müssen (nicht mal wollen, müssen!), nein, wenn es darum geht, dass er die nicht vorhandene Kontrolle verliert, dann wird mit Waffen geschossen, die ich nicht mal meiner Ex antun würde (Und der wünsch ich alle paar Monate lebenslänglich Durchfall).

## Fazit

Aufgrund der Drohung, Nötigung, und dem scheinheiligen Verhalten von `theo_box` sind mit der Veröffentlichung dieses Briefes folgende Dinge in Kraft getreten:

Ich habe die Änderungen am Core rückgängig gemacht, der `112er` Core wurde somit im Server Netzwerk wieder gesperrt und der original Zustand wiederhergestellt, so das nur noch der `111er` und `110er` Core funktionieren (ihr sollte also den vorherigen Core installieren).

Die phpGUI und JavaGUI zeigen für die GUI News und das Abholen der Serverliste wieder auf die applejuicenet.DE Domain.

Die [Github Organisation](https://github.com/appleJuiceNET) wurde vollständig an `theo_box` übertragen.

Die drei Knast*Server wurden abgeschaltet (ja `theo_box`, ich weiß, das der KnastBRUDER nicht benötigt wird, er macht das Leben lediglich einfacher für Neulinge).

Der "appleJuiceNET" Discord Bot wurde abgeschaltet.

Die Linux Snapcraft Packages wurden an `theo_box` übertragen.

Die appleJuice Browser Erweiterungen wurden in den Stores an `theo_box` übertragen.

Die Docker Hub Organisation wurde an `theo_box` übertragen.

Es hat mir Spaß gemacht, ich hab den letzten 18 Monaten viel Neues gelernt, ich habe das alles sehr gern getan, ich habe das alles aus Spaß an der Freude getan, ich habe jede Menge Zeit, Geld (!) und Urlaubstage privat investiert. **Freiwillig**! Das wars bis vor wenigen Tagen auch alles Wert. Schade...

Ihr solltet an der Stelle nur eins wissen: Ihr seid nicht auf ihn angewiesen! Er kann euch nicht drohen (Die Serverbetreiber wissen, was ich meine)!

~~Das Ganze ist als Abschied zu betrachten, ich komme nicht wieder (auch nicht unter einem anderen Nick).~~

Vielen Dank für eure Aufmerksamkeit.

~~**Tschüss**.~~

PS: `theo_box`, wie wir dich mittlerweile alle gut kennen, brennt dir gerade erneut eine Synapse durch und du bist kurz davor etwas sehr Dummes zu tun, solltest du in dem Fall in Erwägung ziehen, meine `Klardaten` zu veröffentlichen, bekommen wir beide richtige Probleme!

PPS: `theo_box`, ich habe dich kurz veröffentlichen dieses Briefes außerdem überall gelöscht und blockiert. Ich werde keinerlei Nachrichten von dir lesen oder beantworten. Wir sind durch. Du hast es nicht verdient dieses Netzwerk zu betreuen. 

### Ich wünsche dir, `theo_box`, ebenfalls <ins>lebenslänglich</ins> Durchfall!
