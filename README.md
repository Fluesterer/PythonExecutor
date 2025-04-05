# 🐍 Python Script Executor

Ein leistungsstarkes, aber benutzerfreundliches Tool zur Ausführung von Python-Code, Installation von Paketen und Verwaltung von `.py`-Dateien – alles in einer modernen, dunklen GUI. Ideal für Programmieranfänger, Schüler und Entwickler, die schnell und einfach Python-Code testen möchten.

---

## ✨ Features

- 🧠 **Code Ausführen:** Schreibe Python-Code direkt im Editor und führe ihn aus. Erhalte sofortige Konsolenausgaben in einer eingebauten Konsole.
- 📦 **Paketinstallation:** Installiere Python-Pakete mit einem Klick durch die GUI (z. B. `pip install <Paketname>`).
- 📋 **Installierte Pakete anzeigen:** Zeige alle derzeit installierten Python-Pakete an.
- 💾 **Speichern und Laden von Code:** Speichere deinen Python-Code als `.py`-Datei oder lade bereits existierende Python-Dateien.
- 📚 **Einsteigerfreundliches Tutorial:** Ein eingebautes Tutorial hilft dir, Python und `pip` zu installieren und grundlegende Befehle auszuführen.
- 🎨 **Dunkles Design:** Modernes und anpassbares Darkmode-UI basierend auf `tkinter`.
- 🔒 **Sicherheitsfeatures:** Verhindert, dass schadhafter Code unabsichtlich ausgeführt wird, indem der Code in einem sicheren Umfeld getestet wird.

---

## 🛠️ Voraussetzungen

- **Python 3.6 oder neuer**  
  (wird empfohlen, da ältere Versionen möglicherweise nicht vollständig unterstützt werden)
- **pip:** Die Python-Paketverwaltung sollte installiert sein (wird in der Regel zusammen mit Python installiert).

---

## ▶️ Nutzung

### 1. Installation

#### Installiere Python:

Lade Python von der offiziellen Webseite [python.org](https://www.python.org/downloads/) herunter, falls es noch nicht installiert ist.

#### Installiere die erforderlichen Abhängigkeiten:

Falls nötig, installiere alle Abhängigkeiten (z. B. `tkinter` für die GUI) mit:

``bash
pip install -r requirements.txt


#  Entwicklersicherheitshinweis
Da das Tool die exec()-Funktion verwendet, um benutzerdefinierten Code auszuführen, besteht immer ein gewisses Risiko. Der ausgeführte Code hat vollen Zugriff auf das System, was dazu führen kann, dass schadhafter Code Systemdateien modifiziert, sensible Daten offenlegt oder das System anderweitig gefährdet.

Wichtige Sicherheitshinweise:
Vermeide das Ausführen von unsicherem Code:

Führe nur Code aus, dem du vertraust.

Vermeide das Ausführen von Code aus unbekannten oder unsicheren Quellen.

Sandboxing:

Es wird empfohlen, den Code in einer sicheren virtuellen Umgebung auszuführen (z. B. mit einer isolierten virtuellen Python-Umgebung), um das Risiko zu minimieren.

Verantwortung der Nutzer:

Es liegt in der Verantwortung des Nutzers, sicherzustellen, dass der ausgeführte Code keine ungewollten Auswirkungen hat.

Verwendung von exec() und Alternativen:

Sei vorsichtig beim Einsatz von exec(). In vielen Fällen gibt es sicherere Alternativen, wie das Verwenden von Funktionen oder das Ausführen von Code in einer kontrollierten Umgebung.

#  👨‍💻 Entwickler
Dieses Projekt wurde mit ❤️ von Yep Studios & Slimecraft Studios entwickelt.
