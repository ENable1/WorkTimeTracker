# Arbeitszeit-Tracker

Ein leistungsstarker **Arbeitszeit-Tracker** entwickelt in **Kotlin**, um Arbeitszeiten effizient zu erfassen, Überstunden zu berechnen und gespeicherte Zeiten komfortabel zu verwalten. Die App bietet eine transparente Übersicht über geleistete Stunden und hilft bei der genauen Dokumentation der Arbeitszeiten.

## Funktionen
- **Zeiterfassung** mit Start- und Endzeit
- **Automatische Berechnung von Überstunden** basierend auf den individuellen Arbeitszeiten
- **SQLite-Datenbank** zur lokalen Speicherung und Verwaltung der Arbeitszeiten
- **Anpassbarer Datenbankpfad** zur individuellen Nutzung
- **Moderne Benutzeroberfläche** mit *Material Design*
- **Personalisierung**: Anpassbare Farben und Arbeitszeiten in den Einstellungen
- **Dark Mode-Unterstützung** für angenehme Nutzung bei verschiedenen Lichtverhältnissen
- **Kalenderansicht** zur Visualisierung aller erfassten Arbeitszeiten
- **Urlaubsverwaltung** zur Erfassung von Urlaubszeiten
- **Exportfunktion** für Arbeitszeitdaten im CSV-Format

## Installation

1. **Repository klonen:**
   ```sh
   git clone https://github.com/ENable1/WorkTimeTracker.git
   ```
2. **Projekt in IntelliJ IDEA öffnen**
3. **Abhängigkeiten auflösen und Anwendung starten**
4. **Datenbank konfigurieren**, falls ein individueller Speicherpfad benötigt wird
5. **Erste Arbeitszeiten erfassen und App an individuelle Bedürfnisse anpassen**

## Screenshots & Benutzeroberfläche

### **Hauptbildschirm**
Zeigt eine Übersicht der erfassten Arbeitszeiten sowie berechnete Überstunden. Die aktuelle Tageszeit wird angezeigt und Nutzer können neue Zeiten erfassen oder vorhandene Einträge verwalten.

![grafik](https://github.com/user-attachments/assets/5d54e8f0-5265-4218-a06b-fd5f0fac58fa)

### **Bearbeiten von Einträgen**
Zeigt ein Dialog, durch welchen man einen eingegebenen Eintrag bearbeiten kann.

![grafik](https://github.com/user-attachments/assets/c473a0ba-d352-4786-b1df-f3ed85166612)

### **Einstellungen**
Hier lassen sich Farbschema, Arbeitszeiten und der Dark Mode konfigurieren. Zudem kann festgelegt werden, ob Erinnerungen zur Zeiterfassung erscheinen sollen.

![grafik](https://github.com/user-attachments/assets/59233733-0793-4c7f-a9f1-360045ddc604)
![grafik](https://github.com/user-attachments/assets/c855ac7f-b111-4d65-b408-99ef28dd2194)


### **Kalenderansicht**
Ermöglicht eine Übersicht aller erfassten Arbeitszeiten über einen längeren Zeitraum zur Identifizierung von Trends oder Unregelmäßigkeiten.

![grafik](https://github.com/user-attachments/assets/01f13d16-9b3c-40ad-b06c-e0e477ca2bba)

## Datenbank
Die App nutzt eine **SQLite-Datenbank** zur sicheren Speicherung der Arbeitszeiten. Der Speicherpfad ist konfigurierbar und kann an individuelle Anforderungen angepasst werden.

## Lizenz
Dieses Projekt steht unter **Lizenz** – Details sind in der [LICENSE](LICENSE) Datei einsehbar.

## Entwickler
- **[Chris](https://github.com/ENable1)**
- **[Marvin](https://github.com/DonMarv00)**

## Geplante Erweiterungen
- [ ] **Web-Interface** zur Verwaltung der Arbeitszeiten über den Browser
- [ ] **Unterstützung für mehrere Benutzerprofile** innerhalb der App
- [ ] **Erweiterte Statistikfunktionen** mit detaillierter Graphenansicht
- [ ] **Windows-Benachrichtigungen** zur Erinnerung an die Zeiterfassung
- [ ] **Datenexport in verschiedene Formate:**
    - [ ] PDF
    - [ ] Excel
- [ ] **Möglichkeit zur Eintragung von Krankentagen**
- [ ] **Urlaubsrechnung**
- [ ] **Cat Mode**
- [ ] **Rufbereitschafts** für Personen welche keine geregelten Arbeitszeiten haben
- [ ] **CSV Converter** mit Versionserkennung
