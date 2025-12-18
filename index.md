# Fenster-zur-Welt – Prototyp Box  
*Temporäre Kurzdokumentation*

Diese Dokumentation beschreibt die grundlegende Nutzung der **Fenster-zur-Welt Prototyp Box**.

---

## Box

Zum Betrieb der Box wird ein **normaler Kaltgerätestecker** benötigt.

👉 **Einschalten:**  
Die Box startet automatisch, sobald das Stromkabel auf der Rückseite eingesteckt wird.

⏱️ **Startdauer:**  
Nach dem Einstecken kann es **bis zu einer Minute** dauern, bis die Box hörbar reagiert.  
Sollte **nach 1–2 Minuten** noch nichts passiert sein, liegt vermutlich ein Defekt vor.

---

## Bedienelemente

Die Box verfügt über **vier Knöpfe**:

- 📷 **Foto** (weiß)
- ✅ **Ja** (grün)
- ❌ **Nein** (rot)
- 🔁 **Repeat** (gelb)

Zusätzlich besitzt die Box **zwei Betriebsmodi**:

### 1. Fenster-Modus
Der **normale Betriebsmodus**, in dem Konversationen geführt werden können.  
Beim Start in diesen Modus ertönt ein **Startup-Signalton**.

### 2. Konfigurations-Modus
Dieser Modus wird aktiviert, wenn **kein WLAN** verfügbar ist.  
Die Box fordert dann dazu auf, die Konfiguration über die App zu überprüfen (siehe unten).

---

## Konfiguration

Wenn etwas mit der Konfiguration nicht stimmt (z. B. kein WLAN), weist die Box **akustisch** darauf hin.

Da die App aktuell noch nicht nutzbar ist, gibt es einen **Ersatz-QR-Generator**:

👉 **QR-Generator:**  
<https://n-jaeger.github.io/fenster-how-to-box/qr.html>

**Vorgehen:**

1. WLAN-Name und Passwort im QR-Generator eintragen  
2. Den erzeugten QR-Code in die Box legen  
3. **Foto-Knopf kurz drücken**  
   - Es sollte ein Signalton ertönen, wenn das Foto aufgenommen wurde
4. Nach kurzer Zeit sollte die Box automatisch in den **Fenster-Modus** wechseln

---

## Fenster-Modus

### Funktionen

- 📷 **Foto aufnehmen:**  
  Im Fenster-Modus **kurz** den Foto-Knopf drücken, um ein Bild eines Gegenstands in der Box aufzunehmen  
  → Signalton bestätigt die Aufnahme

- ✅❌ **Antwort auswählen:**  
  Sobald die Box mit einer Nachricht fertig ist, kann **kurz**:
  - der **Ja-Knopf** oder  
  - der **Nein-Knopf**  
  gedrückt werden, um die entsprechende Aktion auszuführen (Signalton)

- 🔁 **Repeat-Knopf (kurz):**  
  Es gibt zwei mögliche Aktionen:
  - **Die Box spricht gerade:**  
    → Der letzte Satz wird wiederholt
  - **Die Box spricht nicht:**  
    → Die komplette Nachricht seit der letzten Eingabe wird wiederholt

- 🛑 **Konversation abbrechen:**  
  Den **Repeat-Knopf lange** drücken  
  - Dauer: ca. **3 Sekunden**, bis zum Signalton  
  - Funktioniert **jederzeit**, auch wenn gerade keine Konversation aktiv ist  

  💡 *Tipp:*  
  Wenn unklar ist, ob die Box noch „läuft“, einfach diese Funktion nutzen.

---

## Allgemeine Funktionen

Diese Funktionen können **jederzeit** verwendet werden.

### Box herunterfahren

- Den **Foto-Knopf lange** drücken  
  - Dauer: ca. **5 Sekunden**, bis zum Signalton
- Die Box erklärt anschließend das weitere Vorgehen:
  - ✅ **Ja-Knopf:** Box wirklich herunterfahren  
    *(erst möglich, nachdem die Box den Satz beendet hat)*
  - ❌ **Nein-Knopf:** Herunterfahren abbrechen  
    *(ebenfalls erst nach Ende der Sprachausgabe)*

---

### Update-Funktion

Falls während der Testphase ein Update benötigt wird:

1. Den **Repeat-Knopf sehr lange** gedrückt halten  
   - Dauer: ca. **7 Sekunden**, bis zum Signalton  
   - **Wichtig:**  
     Weiter gedrückt halten, auch wenn der „Konversation abbrechen“-Ton kommt
2. Warten, bis die Box neu startet
3. Der erfolgreiche Neustart wird durch den **Startup-Signalton** im Fenster-Modus bestätigt
