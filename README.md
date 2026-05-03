# BPMN XML Modeler

Ein einfaches, funktionales Programm zum Anzeigen und Bearbeiten von BPMN-XML-Dateien.

## 🎯 Features

- **XML-Datei hochladen**: Lade BPMN XML-Dateien direkt auf
- **XML-Code eingeben**: Paste BPMN XML Code direkt in das Textfeld
- **Interaktives Diagramm**: Elemente verschieben, verbinden und neue Elemente hinzufügen
- **Auto-Sync XML**: Änderungen im Diagramm werden automatisch ins XML zurückgeschrieben
- **Responsive Design**: Funktioniert auf Desktop und Tablet
- **Fehlerbehandlung**: Aussagekräftige Fehlermeldungen

## 🚀 Verwendung

### Methode 1: Datei hochladen
1. Öffne `index.html` in einem Browser
2. Klicke auf "📁 Datei laden"
3. Wähle eine `.xml` oder `.bpmn` Datei aus
4. Das Diagramm wird automatisch angezeigt und ist editierbar

### Methode 2: XML direkt eingeben
1. Öffne `index.html` in einem Browser
2. Kopiere BPMN XML Code in das Textfeld
3. Klicke auf "✓ Visualisieren"
4. Das Diagramm wird sofort angezeigt und ist editierbar

## 📄 Testdatei

Eine Beispiel-BPMN-Datei (`example.bpmn`) ist enthalten mit einem einfachen Prozess:
- Start Event
- 2 Tasks
- End Event

## 🛠️ Technologie

- **bpmn-js Modeler**: Kostenlose BPMN-Modeling-Bibliothek
- **HTML5 + CSS3**: Modernes Interface
- **JavaScript**: Dynamische Funktionalität

## 📋 Browser-Kompatibilität

- Chrome (empfohlen)
- Firefox
- Safari
- Edge

## 🎨 Oberfläche

Die Anwendung hat zwei Bereiche:
- **Linkes Panel**: Datei-Upload, XML-Editor und Informationen
- **Rechtes Panel**: Interaktives BPMN-Diagramm (Modeler)

## ⚠️ Anforderungen

- Moderner Webbrowser mit JavaScript-Unterstützung
- Internetverbindung (für bpmn-js Bibliothek von CDN)

## 📝 Hinweise

- Unterstützt BPMN 2.0 XML Format
- Diagramme werden automatisch an die Fenstergröße angepasst
- Änderungen im Diagramm werden automatisch im XML-Textfeld aktualisiert
- Fehlermeldungen helfen bei der Fehlersuche

---

Viel Spaß beim Visualisieren von BPMN-Diagrammen! 🎉
