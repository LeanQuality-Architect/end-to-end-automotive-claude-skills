# 6M-AUDIT-KATALOG & BELEG-REGELN (ANHANG A)

Nutze diesen Katalog in **Phase 2A (6M-Ishikawa)**, um die 6M-Kategorien an die Domäne des Nutzers anzupassen und unbelegte Vermutungen abzuweisen.

## A1: Domäne Produktion & Fertigung
* **Mensch:** Qualifikationsmatrix (nur Rollen, keine Klarnamen!), Einarbeitungsstatus, Schichtwechsel-Übergabe. *Zulässiger Beleg:* Schichtplan-Abgleich über mehrere Anlagen (Kreuzvergleich).
* **Maschine:** Spindel-/Achsverschleiß, Kühlmitteltemperatur, SPS-Parameter, Sensorstatus, Werkzeugstandzeit. *Zulässiger Beleg:* SPS-Datenlogs, Kalibrierscheine, Wartungshistorie.
* **Material:** Chargenschwankungen, Vormaterial-Toleranzen, Lagerbedingungen. *Zulässiger Beleg:* Wareneingangsprüfung, Chargen-Kreuzvergleich auf Parallelanlagen.
* **Methode:** NC-Programmstand, Rüstvorgaben, Prüfpläne, Arbeitsanweisungen. *Zulässiger Beleg:* Versionshistorie, NC-Logfiles, Zeitstudien.
* **Milieu (Umwelt):** Hallentemperatur, Luftfeuchtigkeit, benachbarte Wärmequellen, Abluftleistung. *Zulässiger Beleg:* Datenlogger-Zeitreihen (24-h-Profil), Energie-Lastgänge.
* **Messung:** Prüfmittel-Fähigkeit, Messzeitpunkt (Temperaturausgleich), Kalibrierstatus. *Zulässiger Beleg:* MSA-Studie (%GRR < 10 %, ndc ≥ 5), Kalibrierprotokoll.

## A2: Domäne IT & Software-Engineering
* **Mensch (Rollen):** Code-Review-Abdeckung, Deployment-Berechtigungen, On-Call-Übergabe. *Zulässiger Beleg:* Git-Commit-Logs, Freigabe-Audit-Trails.
* **Maschine (Infrastruktur):** CPU/RAM-Auslastung, Datenbank-Locks, Netzwerk-Latenz, Container-Limits. *Zulässiger Beleg:* APM-Metriken, Server-Logs, Monitoring-Zeitreihen.
* **Material (Daten & Inputs):** API-Payloads, Schema-Abweichungen, Datenqualität, Drittanbieter-Feeds. *Zulässiger Beleg:* Request/Response-Logs, Dead-Letter-Queues.
* **Methode (Prozesse):** CI/CD-Pipeline, Feature-Flags, Caching-Strategie, Rollback-Prozedur. *Zulässiger Beleg:* Pipeline-Logs, Konfigurations-Diffs.
* **Milieu (Last & Umfeld):** Traffic-Spitzen, Batch-Jobs zu bestimmten Uhrzeiten, externe Abhängigkeiten. *Zulässiger Beleg:* Load-Balancer-Statistiken, Cron-Zeitpläne.
* **Messung (Observability):** Log-Vollständigkeit, Alert-Schwellenwerte, Metrik-Granularität. *Zulässiger Beleg:* Trace-Analysen, Testabdeckungs-Berichte.

## A3: Domäne Büro, Verwaltung & Service
* **Mensch (Rollen):** Vertretungsregelungen, Rollenklarheit, Einarbeitungs-Checklisten. *Zulässiger Beleg:* Ticket-Verteilungsstatistik (anonymisiert).
* **Maschine (Systeme & Tools):** ERP/CRM-Masken, Schnittstellen-Abbrüche, Software-Performance. *Zulässiger Beleg:* System-Fehlermeldungen, Schnittstellen-Logs.
* **Material (Informationen):** Unvollständige Kundenangaben, veraltete Vorlagen, fehlerhafte Stammdaten. *Zulässiger Beleg:* Stichprobenauswertung fehlerhafter Vorgänge ($n$).
* **Methode (Workflows):** Genehmigungsschleifen, Medienbrüche (PDF → Excel → ERP), fehlende Pflichtfelder. *Zulässiger Beleg:* Prozess-Durchlaufzeit-Logs, System-Konfiguration.
* **Milieu (Rahmenbedingungen):** Monats-/Quartalsabschluss-Spitzen, parallele Sonderprojekte. *Zulässiger Beleg:* Ticket-Eingangsvolumen nach Kalenderwoche/Uhrzeit.
* **Messung (KPIs):** Definition von SLA-Fristen, Erfassungszeitpunkt im System. *Zulässiger Beleg:* SLA-Report-Abfrage, Stichproben-Audit.

## A4: Auditor-Checkliste für Exit-Gate 2A
Jede Ursache ($X$), die in die 5-Why-Bohrung (Phase 2B) übernommen wird, muss drei Kriterien erfüllen:
1. **Spezifität:** Exakte Benennung von Ort, Zeitpunkt, Parameter oder Teilsystem.
2. **Faktenbeleg:** Vorlage eines objektiven Nachweises (Log, Messreihe, Stichprobe $n$).
3. **Variation:** Nachweis, dass sich $X$ genau dann verändert, wenn auch $Y$ auftritt (IS vs. IS-NOT).
