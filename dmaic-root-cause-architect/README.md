# DMAIC Root-Cause Architect (Claude Skill – Baustein 1)

- **Lokales Verzeichnis:** `C:\Users\eisca\Desktop\KI_dmaic_root_cause_architect_skill\dmaic-root-cause-architect`
- **Stand:** 26.11.2026
- **Suite-Rolle:** Baustein 1 der End-to-End Automotive Suite (Eskalations- und Problemlösungs-Subroutine)

Ein kompromissloser, streng daten- und faktenbasierter Problemlösungs-Skill für **Claude (Desktop, Web & Claude Code)**. Er kombiniert klassische Methoden des Qualitätsmanagements zu einer lückenlosen Audit-State-Machine nach der Formel **$Y = f(X)$**.

## Einordnung in die End-to-End Automotive Suite
1. **Baustein 1 (`dmaic-root-cause-architect`):** *Dieser Skill.* Eskalations- und Problemlösungs-Subroutine bei Gate-Verzug, RCAR-Kostenüberschreitung, fehlgeschlagenem `[FAKT-SERIE]`-Versuch oder kritischen Feld-Reklamationen.
2. **Baustein 2 (`vda-kickoff-sla-architect`):** Präventive Reifegradabsicherung (VDA MLA RG0–RG7) im Simultaneous Engineering.
3. **Baustein 3 (`workshop-readiness-architect`):** Globaler Servicenetz-Rollout (Workshop Readiness) ab RG6/RG7 bis SOP und EOP + 10 Jahre.

## Methoden-Architektur
1. **DEFINE (Phase 0):** Messbare Soll/Ist-Abweichung ($Y$) und scharfe **IS / IS-NOT**-Abgrenzung.
2. **MEASURE (Phase 1):** Messsystem-Analyse (**MSA / %GRR**) und statistische Baseline ($n$, $C_{pk}$) zur Vermeidung von Scheinkorrelationen.
3. **ANALYZE (Phase 2):** Kontextangepasstes **6M-Ishikawa** (Produktion, IT, Verwaltung) mit strikter Trennung in `[FAKT]` vs. `[HYPOTHESE]` sowie **5-Why-Tiefenbohrung** inklusive **Rückwärtsprüfung ("Deshalb-Probe")** und **Gegenbeweis-Check (Falsifikation)**.
4. **IMPROVE (Phase 3):** **Morphologischer Kasten** zur systematischen Entwicklung kreativer und technischer Lösungsbausteine.
5. **CONTROL (Phase 4):** **Poka-Yoke-Härtung** (technische Zwangsführung statt weicher Schulungen), **Control Plan**, **strenge FMEA-Rückkopplung ($S / O / D$)** und automatisches **A3-Abschlussprotokoll**.

## Eingebaute Schutz-Gates
* **Lösungsverbot:** Blockiert vorzeitige Lösungsvorschläge in den Analysephasen (Phase 0–2).
* **Floskel-Blacklist:** Weist menschliches Versagen (*"Unachtsamkeit"*, *"Schulung"*, *"besser aufpassen"*) als Symptom zurück.
* **Privacy-Gate:** Erzwingt anonymisierte Rollen statt Klarnamen und schützt vor der Eingabe vertraulicher Betriebsgeheimnisse.

## Installation in Claude
1. Lade die Dateien `SKILL.md`, `6M_KATALOG.md` und `A3_PROTOKOLL_VORLAGE.md` (oder die ZIP-Datei `dmaic-root-cause-architect.zip`) hoch.
2. Ziehe alle drei Dateien in einen neuen Chat in **Claude Desktop / Web** und schreibe:
   > *"Erstelle aus diesen drei Dateien den Skill `dmaic-root-cause-architect` inklusive Anhang A und Anhang B und zeige mir die Speichern-Karte."*
3. Klicke in der Karte auf **Speichern**.
4. Starte jederzeit eine Analyse mit dem Befehl `/dmaic-root-cause-architect`.

## Haftungsausschluss (Disclaimer)
Dieses Tool dient ausschließlich der methodischen Strukturierung von Problemanalysen und Workshops. Es ersetzt keine ingenieurtechnische Prüfung, Sicherheitsabnahme oder normative/rechtliche Freigabe (z. B. nach IATF 16949, ISO 9001 oder Maschinenrichtlinie). Die Verantwortung für die fachliche Richtigkeit und Umsetzung der abgeleiteten Maßnahmen liegt allein beim Anwender.

## Lizenz
Veröffentlicht unter der **MIT-Lizenz** (Copyright 2026 LeanQuality-Architect).
