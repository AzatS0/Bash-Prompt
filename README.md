# Linux Befehl Vorhersage und Ausführung mit TensorFlow

Dieses Projekt verwendet TensorFlow, um ein Modell zu trainieren, das basierend auf einer Textbeschreibung eines Linux-Befehls den entsprechenden Befehl vorhersagt und ausführt. Es kombiniert maschinelles Lernen und die Ausführung von Systembefehlen direkt aus der Kommandozeile.

**Hinweis:** Das Projekt enthält keinen originalen Datensatz. Der Datensatz mit den Befehlen und ihren Beschreibungen muss manuell erstellt und hinzugefügt werden. Der Datenbereinigungsprozess ist derzeit nicht implementiert, da das Projekt hauptsächlich als Konzeptidee entwickelt wurde.  
Außerdem ist dieses Projekt derzeit **nur mit Linux** kompatibel. Es kann auf anderen Betriebssystemen wie Windows oder macOS nicht direkt ausgeführt werden.

## Funktionen

- **Datenverarbeitung und Modelltraining**: Ein TensorFlow-Modell wird trainiert, um Linux-Befehle basierend auf ihren Beschreibungen zu erkennen.
- **Vorhersage von Befehlen**: Das Modell kann Vorhersagen für Linux-Befehle treffen, die auf einer Textbeschreibung basieren.
- **Befehlsausführung**: Nach der Vorhersage führt das Programm den vorhergesagten Befehl direkt aus und zeigt die Ausgabe oder Fehler an.

## Installation

1. **Python 3.x installieren**: Stelle sicher, dass du Python 3.x und pip auf deinem System installiert hast.

2. **Virtuelle Umgebung erstellen (optional aber empfohlen)**:

   ```bash
   python3 -m venv venv
   source venv/bin/activate  # Auf Linux/macOS
   ```
3. Abhängigkeiten installieren
   ```bash
   pip install -r requirements.txt
   ```
