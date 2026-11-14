# gw128-hausanschluss-manager

Windows-Anwendung für die Dokumentation von Hausanschlüssen und Rohrleitungsbaumaßnahmen.

Zielgruppen sind Versorgungsunternehmen, Rohrleitungsbaufirmen und fachliche Ausbildungsstätten.

Die aktuelle Windows-Testausgabe ist **1.0.5**.

- [Windows-Installation herunterladen](https://github.com/stephankleinegesse-dev/gw128-hausanschluss-manager/releases/download/v1.0.5/GW128-Setup-1.0.5-x64.exe)
- [Portable USB-Ausgabe herunterladen](https://github.com/stephankleinegesse-dev/gw128-hausanschluss-manager/releases/download/v1.0.5/GW128-Windows-USB-1.0.5.zip)
- [Fünf getrennte Blanko-Aufmaßvorlagen](https://github.com/stephankleinegesse-dev/gw128-hausanschluss-manager/releases/download/v1.0.5/GW128-Blanko-Aufmass-1.0.5.zip)
- [Änderungen und Hinweise](https://github.com/stephankleinegesse-dev/gw128-hausanschluss-manager/releases/tag/v1.0.5)

## Installation und Updates

Die Setup-Datei unter Windows x64 ausführen. Sie legt Desktop- und Startmenü-Verknüpfungen an. Die installierte Ausgabe prüft im Hintergrund auf neue Veröffentlichungen. Nach dem Download wird die Installation ausdrücklich bestätigt; vorher wird das offene Projekt gesichert und nach dem Neustart zur Wiederherstellung angeboten. Eine manuelle Prüfung gibt es unter **Hilfe → Nach Online-Updates suchen**.

Der echte Updateablauf **1.0.2 → 1.0.3** wurde unter Windows erfolgreich geprüft: öffentlicher Download, Installation, Neustart und vollständige Wiederherstellung eines synthetischen, ungespeicherten Testprojekts. Ein weiterer Laptop wurde in diesem Durchlauf nicht getestet.

Die portable Ausgabe vollständig entpacken und `GW128.exe` starten. Sie verwendet **Hilfe → Update aus ZIP installieren**; der automatische Installationsweg gilt für die Setup-Ausgabe.

## PINA einrichten

**PINA → API-Schlüssel verwalten → Verschlüsselt speichern → Verbindung prüfen**. Benötigt wird ein eigener Gemini-API-Zugang. Der Schlüssel wird im Windows-Benutzerkonto verschlüsselt gespeichert; er gehört weder in Projektdateien noch in dieses Repository. Bei bestätigten Anbieteranfragen wird er zur Authentifizierung über HTTPS verwendet.

Der Verbindungstest prüft Zugang und Modellverfügbarkeit, ohne Projektdateien zu senden. Eine erfolgreiche Handskizzenerkennung muss separat mit einer zur Übertragung freigegebenen Datei getestet werden. Ohne verfügbaren Anbieterzugang wird keine erfolgreiche Online-Erkennung behauptet.

## Stand der Testausgabe

Startbildschirm mindestens vier Sekunden, bereinigte Firmenlogoauswahl mit Kleinegesse Engineering, erhaltene GW128-/PINA-Grafiken und aktualisiertes Handbuch. Die allgemeine Erklärung hat eine kontrastreiche Überschrift; ohne gewähltes Logo bleibt kein reservierter Logokasten.

Neu in 1.0.5: Gebäudebezogene Bemaßung und Konsistenzprüfung, überarbeiteter Nordpfeil, separate Blanko-PDFs für fünf Sparten sowie ein Lernsystem mit fünf Anforderungsstufen, 25 Aufgaben und Widerlager-Übungsrechner. Bestehende Inhalte und Arbeitsabläufe bleiben erhalten. Der Rechner dokumentiert sein vereinfachtes Modell und ersetzt keine vollständige Widerlagerbemessung.

Importe werden über eine verfügbare Avira-AMSI-Schnittstelle oder einen aktiven Microsoft Defender geprüft; gesperrte oder nicht prüfbare Dateien werden nicht übernommen. ZIP-Inhalte und eingebettete Anlagen werden berücksichtigt. Schutzprogramme werden nicht umgestellt. Ein Scan ohne Fund garantiert keine Schadsoftwarefreiheit.

Für 1.0.5 bestanden 23 Regressionssuiten, 64 Prüfungen der portablen Windows-Ausgabe und 66 Prüfungen der vorbereiteten NSIS-Laufzeit. Der lokale NAVA-Durchlauf mit aktiver Avira-Prüfung umfasste vier Repack-Testarchive, zehn Teilvermessungen, 174 Punkte, 28 Spartenblätter und 41 Quell-PDFs. Das Handbuch öffnete mit 31 offline geladenen Abbildungen. Die 79 Dateien des USB-Archivs und alle fünf GitHub-Dateien wurden über Prüfsummen abgeglichen. Der öffentliche Updatefeed wurde geprüft; ein vollständiger Installations-/Neustartdurchlauf von 1.0.4 auf 1.0.5 ist noch nicht nachgewiesen. Das ist keine vollständige Prüfung sämtlicher Funktionen oder aller Kundendaten.

Die Anwendung ist noch nicht digital signiert; Windows kann einen unbekannten Herausgeber melden. Es liegt keine DVGW-/rbv-Softwarezertifizierung vor. Die Software ersetzt keine fachliche Prüfung oder Betreiberfreigabe; der lokale Selbsttest ist keine beaufsichtigte Qualifikationsprüfung.

Kundenprojekte, NAVA-Testdaten, Zugangsschlüssel und fremde Originalunterlagen werden nicht in dieses öffentliche Repository aufgenommen.

Entwicklung: Stephan Kleinegesse · Kleinegesse Engineering
