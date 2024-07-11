
# Programmier- und Namensrichtlinien für Structured Text Programmierung bei Beckhoff Steuerungen

## Programmier-Richtlinien

1. **Modularisierung**
   - Zerlege den Code in kleine, wiederverwendbare Funktionen oder Funktionsbausteine.
   - Verwende Bibliotheken, wo immer möglich.

2. **Kommentierung**
   - Kommentiere den Code ausreichend, um die Funktionsweise zu erklären.
   - Benutze Blockkommentare für größere Abschnitte und Inline-Kommentare für spezifische Zeilen.

3. **Strukturierung**
   - Nutze Einrückungen und Leerzeilen, um den Code lesbarer zu gestalten.
   - Gruppiere zusammengehörige Anweisungen logisch.

4. **Fehlerbehandlung**
   - Implementiere eine umfassende Fehlerbehandlung.
   - Nutze TRY-CATCH Blöcke, wo dies möglich ist.

5. **Testbarkeit**
   - Schreibe Code so, dass er leicht getestet werden kann.
   - Erstelle Unit-Tests für kritische Funktionen.

6. **Dokumentation**
   - Halte eine externe Dokumentation der Funktionen und deren Nutzung bereit.
   - Aktualisiere die Dokumentation regelmäßig.

## Namenskonventionen

1. **Variablen**
   - Verwende aussagekräftige und eindeutige Namen.
   - Nutze CamelCase für Variablennamen (z.B. `actualVelocity`, `targetTorque`).

2. **Konstanten**
   - Schreibe Konstanten in Großbuchstaben und trenne Wörter mit Unterstrichen (z.B. `MAX_SPEED`, `TEMPERATURE_THRESHOLD`).

3. **Funktionen und Funktionsbausteine**
   - Benenne Funktionen und Funktionsbausteine mit aussagekräftigen Namen und `FB_` .
   - Nutze CamelCase für Funktionsnamen (z.B. `FB_DriveControl`, `FB_SdoReadWrite`).
   - Intanziierte Funktionsblöcke mit `fb_` (z.B. `fb_DriveControl`, `fb_SdoReadWrite`).

4. **Programme**
   - Programme sollten klar benannt sein und ihren Zweck widerspiegeln (z.B. `MainControlProgram`, `SafetyCheckProgram`).

5. **Datenstrukturen**
   - Benenne Strukturen so, dass ihr Inhalt klar wird (z.B. `MotorParameters`, `SensorData`).
   - Enums (z.B. `E_OpModes`, `E_DriveStates`).
