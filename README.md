# Patient Management App (Java)

Eine einfache Java-Anwendung zur Verwaltung von Patientendaten.  
Das Projekt demonstriert Grundlagen von objektorientierter Programmierung, Datenmodellierung und der Arbeit mit Collections in Java.

## 🎯 Ziele

- Patienten in einem System erfassen, anzeigen, suchen und verwalten
- Saubere Trennung von Datenmodell (Patient), Logik und UI (Konsole)
- Java-Grundlagen für eine kleine Praxis-/Verwaltungssoftware zeigen

## ✨ Features

- Patient anlegen (z. B. Name, ID, Alter / Geburtsdatum, Diagnose etc.)
- Liste aller Patienten anzeigen
- Patienten nach ID oder Namen suchen
- Patientendaten aktualisieren (z. B. Diagnose)
- Patienten aus dem System entfernen
- Einfache Konsolenoberfläche (Menüführung)

> Hinweis: Die Daten werden aktuell im Speicher gehalten (kein persistentes Speichern in einer Datenbank).

---

## 🛠 Tech Stack

- **Sprache:** Java (z. B. Java 17 oder höher)
- **Typ:** Konsolenanwendung
- **Build:** Kompilierung direkt über `javac` oder eine IDE (z. B. IntelliJ IDEA, VS Code)

---

## 📁 Projektstruktur

Grober Aufbau (kann je nach Umsetzung leicht variieren):

```text
patientmanagementApp/
└── java/
    └── com/
        └── patientmanagement/
            ├── Main.java
            ├── Patient.java
            └── ... weitere Klassen (Service, Utils, etc.)
