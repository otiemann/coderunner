# SQL CodeRunner mit verbessertem Precheck

Dieses Repository enthält einen verbesserten Prototyp für SQL-Aufgaben in Moodle mit dem CodeRunner-Plugin. Der Prototyp `sql_improved_precheck` bietet didaktisch sinnvolles Feedback bei Laufzeitfehlern sowie die Möglichkeit eines Prechecks.

## Funktionen

- **Verbessertes Fehler-Feedback**: Didaktisch aufbereitete Fehlermeldungen
- **Precheck-Funktion**: Ermöglicht Studierenden, ihre Antworten vor der endgültigen Bewertung auf Laufzeitfehler zu überprüfen
- **Anpassbare Spaltenbreiten**: Konfigurierbare Darstellung der SQL-Ergebnisse

## Verwendung

1. Importieren Sie die XML-Datei `PROTOTYPE_sql_improved_precheck.xml` in Ihre Moodle-Instanz
2. Erstellen Sie neue SQL-Fragen basierend auf diesem Prototyp
3. Konfigurieren Sie bei Bedarf die Precheck-Optionen und Spaltenbreiten

## Technische Details

Der Prototyp basiert auf dem Standard-SQL-Prototyp des CodeRunner-Plugins, enthält jedoch zusätzliche Features:

- Verbesserte Fehlerbehandlung durch Bereinigung und Formatierung von SQLite-Fehlermeldungen
- Unterstützung für Spaltenbreiten-Konfiguration über den `.width`-Befehl
- Separate Ausführungslogik für Precheck und reguläre Bewertung

## Voraussetzungen

- Moodle mit installiertem [CodeRunner-Plugin](https://coderunner.org.nz/)
- Jobe-Server mit installiertem SQLite3

## Installation

1. Laden Sie die XML-Datei herunter
2. Gehen Sie in Moodle zur Fragenbank
3. Wählen Sie "Importieren" und laden Sie die XML-Datei hoch
4. Stellen Sie sicher, dass das Format auf "Moodle XML Format" eingestellt ist
