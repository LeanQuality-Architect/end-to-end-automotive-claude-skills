# A3-ABSCHLUSSPROTOKOLL: DMAIC ROOT-CAUSE-AUDIT (ANHANG B)

*(Hinweis: Dieses Protokoll wird bei Erreichen von Exit-Gate 4 vollständig ausgefüllt und als exportierbares Claude Doc erstellt).*

---

## 1. PROBLEM-DEFINITION & MESS-BASELINE (DEFINE & MEASURE)
* **Domäne / Prozess:** [Produktion / IT / Verwaltung – anonymisiert]
* **Fehlermerkmal ($Y$) & Spezifikation:** [Soll-Wert, Toleranz, Ist-Abweichung]
* **Statistische Baseline ($n$):** [Stichprobenumfang $n$, Ausschuss-/Fehlerrate %, Mittelwert, Streuung $s$, $C_{pk}$]
* **IS / IS-NOT-Abgrenzung:**
  * **IS (Tritt auf):** [Wo, wann, bei welchem Objekt/Zeitfenster]
  * **IS-NOT (Tritt nicht auf):** [Vergleichsanlage, andere Schicht, anderer Zeitraum]
* **Messsystem-Validierung (MSA):** [Prüfmittel/Methode, %GRR, ndc, Messbedingungen]

---

## 2. URSACHENANALYSE & BEWEISKETTE (ANALYZE: 6M & 5-WHY)
* **Geprüfte & verworfene 6M-Hypothesen:** [Liste der falsifizierten Faktoren]
* **Kritische Einflussgröße ($X$):** [Belegter 6M-Fakt mit Korrelation/Zeitreihe]
* **Verifizierte 5-Why-Kette:**
  1. **Why 1:** [Direkte physikalische/logische Ursache]
  2. **Why 2:** [Zwischenursache]
  3. **Why 3:** [System-/Prozesslücke]
  4. **Why 4:** [Steuerungs-/Wartungsdefizit]
  5. **Why 5 (Systemische Grundursache $Root Cause\ X$):** [Lösungsfreie Beschreibung des Systemzustands]
* **Logik- & Falsifikationstestat:**
  * *Rückwärtsprüfung ("Deshalb"):* [Bestätigt]
  * *Gegenbeweis (Falsifikation):* [Nachweis, dass $Y$ bei Abstellen von $X$ verschwindet]

---

## 3. LÖSUNG & POKA-YOKE-HÄRTUNG (IMPROVE & CONTROL)
* **Gewählte Lösungskombination (Morphologischer Kasten):** [Zusammenfassung der gewählten Parameter]
* **Implementierte Poka-Yoke-Barrieren (Zwangsführung):**
  * [Barriere 1: z. B. Konfigurationsabgleich / Hard-Stopp]
  * [Barriere 2: z. B. Sensor-Fusion / Plausibilitätsprüfung]
  * [Barriere 3: z. B. Geschlossener Durchlasspfad im Einricht-/Wartungsbetrieb]

---

## 4. CONTROL PLAN & WIRKSAMKEITSNACHWEIS

| Prozessschritt / Parameter | Messgröße & Sollwert | Prüffrequenz / Methode | Verantwortliche Rolle | Reaktionsplan bei Abweichung |
| :--- | :--- | :--- | :--- | :--- |
| [Parameter 1] | [Sollwert] | [z. B. 100 % SPS-Echtzeit] | [Rolle] | [Sofortmaßnahme / Stopp] |
| [Parameter 2] | [Sollwert] | [z. B. Wöchentlich / Zustandsbasiert] | [Rolle] | [Eskalation / Wartung] |

* **Wirksamkeitsnachweis (Vorher vs. Nachher):** [Stichprobe $n$ nach Umsetzung, neue Fehlerrate %, neuer $C_{pk}$-Wert]

---

## 5. FMEA-RÜCKKOPPLUNG (PFMEA-UPDATE)

| Kennzahl | Vor Maßnahme (Alt) | Nach Maßnahme (Neu) | Audit-Begründung |
| :--- | :--- | :--- | :--- |
| **S (Bedeutung)** | [1–10] | [unverändert] | [Keine Konstruktionsänderung am Produkt/Ergebnis] |
| **O (Auftreten)** | [1–10] | [1–10] | [Beleg durch Wirksamkeitsmessung unter aktiven Stressbedingungen] |
| **D (Entdeckung)** | [1–10] | [1–10] | [Beleg durch Poka-Yoke-Zwangsführung & geschlossene Durchlasspfade] |
| **RPZ ($S \times O \times D$)** | [Alt] | [Neu] | [Risikoreduktion in %] |

* **Status:** `[Gates 0–4 verifiziert | Umsetzung abgeschlossen | Wirksamkeitsnachweis dokumentiert]`
