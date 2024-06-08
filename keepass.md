# KeePass
Um ohne weiter erklärungen zum Einrichten zu kommen gehe in den Abschnitt [Installation](#Installation)

## Installation - Windows
Um KeePass unter Windows zu installierne gehe auf die offiziele [Webseite von KeePassXC in den Bereich Donloads](https://keepassxc.org/download/#windows) und lade dir dort das Installations Programm für Windows herunter.
1. Sobald der Download abgeschlossen ist, starte die heruntergeladene Datei. Nun sollte sich ein Installer Fenster öffnen.
2. Im ersten Fenster wirst du gefragt, ob du die Lizenz akzeptierst.
KeePassXC ist **freie Software**, das bedeutet das mit dieser Lizenz dem Nutzer bestimmte Rechte zugesichert werden und du volle Kontrolle über das Programm hast. Im Gegensatz zu den meisten anderen Programmen die viel genutzt werden.
Bei diesen wirst dann oft darauf Hingewiesen das du zustimmt, das deine Daten verarbeit werden.
Setze den Hacken bei `I accept the terms in the License Agriment` und klicke auf `Weiter`.
4. Im sich nun öffnenden Fenster sollst du auswählen wo das Programm installiert wird. Im Regelfall muss dort nichts geändert werden, klicke auf `Weiter`.
5. Klicke auf `Installieren` und bestätiege wenn Notwendig als Administrator.
6. Im nächsten Fenster noch auf Fertig und weiter geht es mit der Einrichtung

## Einrichtung
Willst du KeePass mit der Nextcloud nutzen, solltest du vorher noch diese [Anleitung](nextcloud_windows.md) befolgen und im zum Punkt Einrichten mit Nextcloud springen

### Einrichten mit Nextcloud
1. Starte KeePassXC falls es noch nicht geöffnet ist und wähle im sich öffnenden Fenster `+ Datenback erstellen`.
2. Vergebe im neuen Fenstere einen Namen für die neue Passwort Datenbanck wie z.B. `Passwörter` und klicke auf `Weiter`.
3. Im nächsten Fenster musst du nichts einstellen, außer du willst die Datenbank noch sicherer machen als sie ohnehin schon ist. Klicke wieder auf `Weiter`
4. Jetzt kommen wir zu einem wichtiegen Schritt, dem Passwort für deine Datenbanck. Wie bei der Herr der Ringe wählen wir jetzt ein Passwort um sie alle zu Knechten. Das heißt wähle ein möglichst Sichers Passwort, dass du dir gut merken kannst. Das ist dan das eine Passwort, was du im Kopf haben musst. Eine gute Strategie ist es, sich einen Satz auszudencken, den man sich gut merken kann und von diesem immer die Anfangsbuchstaben für sein Passwort zu nehmen. Beispielhaft wird aus dem Satz `Diese Anleitung erklärt mir, wie ich mir nur 1 sehr gutes Passwort zu merken brauche` das Passowrt `DAemwimn1sgPzmb`. Weiter Informationen zur Wahl einers sicheren Passwortes gibt es auf der Seite vom [BSI](https://www.bsi.bund.de/DE/Themen/Verbraucherinnen-und-Verbraucher/Informationen-und-Empfehlungen/Cyber-Sicherheitsempfehlungen/Accountschutz/Sichere-Passwoerter-erstellen/sichere-passwoerter-erstellen.html?nn=131350).
5. Du kannst dir den Satz auch auf einen Zettel schreiben, bewahre diesen aber sicher zu Hause auf. Wenn du z.B. den ersten oder letzten Satz aus deinem Lieblingsbuch nimmst, sparst du dir diesen Schritt.
6. Gebe dein Passowrt ein und klicke auf `Fertig`.
7. Jetzt wirst du noch gefragt, wo du deine Passowrt Datenbank speichern möchtest. Wähle den `Nextcloud` Ordner und erstelle darin einen neuen Ordner mit z.B. dem Namen `keepass`. Navigiere in diesen und klicke auf `Speichern`. Deien Datenbank ist fertig, wird von Nextcloud syncronisiert kann genutzt werden.

## Passwörter automatisch im Browser (Firefox oder Chrome)
Möchtest du, wenn du auf eine Webseite besuchst deine Passwörter beim Login automatisch eingegeben werden, musst du für deinen Browser noch ein Plugin installieren und dieses aktivieren.

### In Firefox
1. Öffne KeePassXC und gehe über das `Zahnrad` in die Einstellungen und naviegiere Links zum Punkt `Browser Integration`
2. Setze oben einen Hacken bei `Enable browser integration`
3. Setze einen Hacken bei `Firefox und Tor Browser` und klcike unten auf `OK`
4. Öffne Firefox und installiere die [KeePassXC-Browser](https://addons.mozilla.org/en-US/firefox/addon/keepassxc-browser/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search) Erweiterung
5. Klicke im Firefox oben auf das `Puzzle Symbol` und anschließend auf die `KeePassXC` Erweiterung.
6. Jetzt öffnet sich ein kleines Fenster in dem du auf `Verbinden` drückst und anschließend aufgevordert wirst einen Namen zu vergeben. Dieser ist nicht wichtig, z.B. `KeePass Firefox`.
7. Jetzt solltest du verbunden sein und die Passwörter in deiner Datenbank werden automatisch in die Webseite gefüllt.