# Verbindliche VDA-MLA Gate-Checkliste (RG0 bis EOP + 10 Jahre)

- **Referenz-Skill:** `vda-kickoff-sla-architect` (`C:\Users\eisca\Desktop\KI_vda_kickoff_sla_architect_skill`)
- **Stand:** 26.11.2026
- **Hinweis:** Jedes Prüfergebnis muss mit einem Evidenz-Tag (`[CAD-VORBEHALT]`, `[FAKT-LABOR]` oder `[FAKT-SERIE]`) versehen werden.

---

## RG0 – Projekt-Kick-off & Konzeptdefinition
- [ ] **SE-Präsenz:** AS-Engineer ist ab Sekunde 1 im SE-Team aller relevanten Gewerke verankert.
- [ ] **Bringschuld 1 (RCAR-Zielwerte):** Maximal zulässige Reparaturkosten (ET + AW + Lack/Kalibrierung) für die Ziel-Typklasse definiert und im Lastenheft hinterlegt.
- [ ] **ABC-Risiko-Triage (Start):** Erste Identifikation von A-Teilen (RCAR/Crash/Außenhaut, > 1.500 €, HV, ADAS).
- [ ] **RFQ-Standardbausteine:** SLA-Anforderungen (Minimum-Plus-Regel, Konservierung, LTB-Fristen, UN-R155/Flashware) im Lastenheft integriert.

## RG1 – Konzept-Freeze & Lastenheft-Verabschiedung
- [ ] **ABC-Triage finalisiert:** Vollständige Einstufung aller Umfänge in A-Teile (volles SLA), B-Teile (Checkliste) und C-Teile (ohne Kick-off-Aufwand).
- [ ] **Minimum-Plus-Abgleich:** Werks-Nacharbeitskonzepte (Ausschleusstation) erfasst; Ersatzverfahren für nicht-werkstatttaugliche Technologien (Laser, Bolzenschießen, KTL) konzipiert.
- [ ] **Typklassen-Veto-Prüfung:** Konzeptbewertung gegen RCAR-Kostendeckel abgeschlossen; bei Gefährdung Verursacher-Prinzip (R&D/Tooling-Budget) angemeldet.

## RG2 – Serienvergabe & Lieferanten-Nominierung
- [ ] **Anti-Buy-in-Regel erfüllt:** Serienpreis, ET-Preise (Stufe 1), vorveredelte Reparaturkits (Stufe 2) und ET-Preisfaktor zeitgleich angefragt und vor Nominierung vertraglich fixiert.
- [ ] **Elektronik-Verpflichtung:** 10 Jahre Abwärtskompatibilität von Diagnose-/Flash-Routinen und Flashware-Hinterlegung beim OEM vertraglich gesichert.
- [ ] **LTB-Klausel:** Mindestens 12 Monate Ankündigungsfrist für Last-Time-Buy vereinbart.
- [ ] **Ausnahme-Check Sonderwerkzeug:** Prüfung, ob völlig neue Gerätetechnologie ohne Marktbasis einen begründeten Frühstart (`[FAKT-LABOR]`) erfordert.

## RG3 – Konstruktions-Freeze (Digitale DMU-Absicherung)
- [ ] **Evidenz-Tag `[CAD-VORBEHALT]`:** Bauraum, Werkzeug-Zugänglichkeit und Demontagepfade im DMU vollständig geprüft (noch keine reguläre AS-Werkzeugbestellung).
- [ ] **Bringschuld 2 (Lösungen statt Kritik):** Für jede DMU-Ablehnung liegt ein konstruktiver Gegenvorschlag vor (z. B. Flanschbreite Setzkopf, Trennstelle vor Crashzone).
- [ ] **Pflichtfrage 1 (Homologation):** Zulassungsrechtliche Erlaubnis des Reparaturverfahrens bestätigt.
- [ ] **Pflichtfrage 2 (Cybersecurity/Diagnose):** Diagnose- und Komponentenschutz-Freischaltung (UN-R155) für freie und autorisierte Werkstätten geklärt.
- [ ] **Pflichtfrage 3 (HV-Sicherheit):** HV-Dichtheits- und Isolationsprüfung unter Werkstattbedingungen technisch abgesichert.

## RG4 – Produktions- & Werkzeugfreigabe (Start Partner-Werkzeugbau)
- [ ] **Bringschuld 3 (Business Case):** Für AS-Sonderwerkzeuge außerhalb der Typklassen-Rettung liegt ein positiver Amortisationsnachweis über Garantie-/Kulanzeinsparungen vor.
- [ ] **Werkzeug-Beauftragung:** Partner-Werkzeughersteller (Werkzeug-Stufe B/C) auf Basis des freigegebenen RG3-DMU beauftragt.
- [ ] **AIAG-VDA FMEA-Abgleich:** Service- und Nacharbeitsrisiken in Design- und Prozess-FMEA berücksichtigt.

## RG5 – Vorserie & Physische Validierung (`[FAKT-SERIE]`)
- [ ] **Pflicht-Evidenz `[FAKT-SERIE]`:** Physische Reparaturerprobung am serienfallenden Gesamtzusammenbau (inkl. Störkonturen, Dichtungen, KTL, Worst-Case-Toleranz) erfolgreich unter Werkstattbedingungen durchgeführt.
- [ ] **100 % Originalzustand:** Nachweis über Wiederherstellung von Crash, Korrosion, EMV, Homologation und Diagnose erbracht.
- [ ] **Eskalations-Gate:** Bei fehlgeschlagenem `[FAKT-SERIE]`-Versuch oder RCAR-Überschreitung -> Automatische Übergabe an Baustein 1 (`dmaic-root-cause-architect`).

## RG6 – Prozess- & Produktfreigabe (VDA 2 / PPF)
- [ ] **VDA-2-Kopplung:** Keine uneingeschränkte VDA-2-/PPF-Freigabe ohne freigegebene Werksnacharbeit (BGH „fabrikneu“) und AS-Reparaturverfahren.
- [ ] **ET-Konservierung & Stufen:** Zertifizierter Lager-Korrosionsschutz (KTL, Konservierungsöl, VCI-Verpackung) freigegeben; Stufe-1-Basisteile und Stufe-2-Reparaturkits/Pigtails angelegt.
- [ ] **Arbeitswerte (AW):** Verifizierte Zeitstudien/AW aus dem `[FAKT-SERIE]`-Versuch dokumentiert.
- [ ] **Handover Baustein 3 (Start):** Übergabe aller Verfahren, ET-Kits, Sonderwerkzeuge und AW an `workshop-readiness-architect`.

## RG7 – SOP & Serienanlauf
- [ ] **Servicenetz-Bereitschaft:** Freigabebestätigung von Baustein 3 (`workshop-readiness-architect`) für globalen Rollout liegt vor.
- [ ] **Controlling-Kurve aktiv:** Kleinteilige Stufe-2-Reparaturkits sind für die Garantie- und Typklassen-Hochphase (Serie bis EOP + 3–5 Jahre) verfügbar.

## EOP bis EOP + 10 Jahre – Später Aftermarket & Auslauf
- [ ] **Bringschuld 4 (ET-Konsolidierung / LTB):** Bei LTB-Ankündigung (mind. 12 Monate Vorlauf, ca. Jahr 5–10 nach EOP) kontrollierte Hochstufung auf Baugruppen zur Senkung von Lager-/VCI-Kosten durchgeführt.
- [ ] **Werkzeug-Kompatibilität:** Einbau der hochgestuften Baugruppen mit vorhandenen Werkstattwerkzeugen ist verifiziert.
- [ ] **Flashware- & Diagnose-Sicherung:** Abwärtskompatibilität der Diagnose-/Flash-Routinen und Hinterlegung der Flashware beim OEM bis EOP + 10 Jahre sichergestellt.
