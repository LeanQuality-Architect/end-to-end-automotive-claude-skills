# End-to-End Automotive Quality & After-Sales Suite (Claude Skills)

![End-to-End Automotive Suite](./End-to-End%20Automotive%20Suite.png)




Eine modulare Suite aus drei spezialisierten **Claude Skills** für die präventive Reifegradabsicherung, datenbasierte Problemlösung und weltweite Service-Readiness in der Automobilindustrie (VDA MLA RG0–RG7 bis EOP + 10 Jahre).

## Architektur der Suite

| Baustein | Skill-Name | Fokus & Lebenszyklus-Phase |
| :--- | :--- | :--- |
| **Baustein 1** | [`dmaic-root-cause-architect`](./dmaic-root-cause-architect) | Datenbasierte Root-Cause-Analyse ($Y = f(X)$), 6M-Ishikawa, 5-Why mit Falsifikation, Poka Yoke & FMEA-Rückkopplung ($S/O/D$). Dient zugleich als Eskalations-Subroutine bei Gate-Verzug. |
| **Baustein 2** | [`vda-kickoff-sla-architect`](./vda-kickoff-sla-architect) | Präventive Reifegradabsicherung (VDA MLA RG0–RG7, VDA 2 / PPF) aus Sicht des OEM After-Sales-Engineers inkl. RCAR-Typklassen-Schutz, Anti-Buy-in-Check & 3-stufiger Evidenz (`[CAD-VORBEHALT]`, `[FAKT-LABOR]`, `[FAKT-SERIE]`). |
| **Baustein 3** | [`workshop-readiness-architect`](./workshop-readiness-architect) | Globaler Servicenetz-Rollout ab RG6/RG7 bis SOP und EOP + 10 Jahre (Reparaturliteratur, ET-Stufe 1/2, Sonderwerkzeuge, UN-R155/Flashware & Training). |

## Installation in Claude
1. Lade die gewünschten Skill-Pakete unter **Releases** (oder die jeweiligen `SKILL.md`- und Referenzdateien aus den Unterordnern) herunter.
2. Öffne in **Claude Desktop / Web** das Menü **Einstellungen → Plugins → Hinzufügen → Plugin hochladen**.
3. Wähle die jeweilige `.zip`- oder `SKILL.md`-Datei aus und aktiviere den Skill.

## Haftungsausschluss & Markenhinweis (Disclaimer)
Dieses Repository dient ausschließlich der methodischen Strukturierung von Qualitäts-, Engineering- und Service-Rollout-Prozessen. Es ersetzt keine ingenieurtechnische Prüfung, Sicherheitsabnahme oder normative/rechtliche Freigabe (z. B. nach VDA, IATF 16949, ISO 9001 oder UN-Regelungen). Die Verantwortung für die fachliche Richtigkeit und Umsetzung der abgeleiteten Maßnahmen liegt allein beim Anwender. Genannte Standards und Marken (z. B. VDA, AIAG, RCAR, Claude) sind Eigentum der jeweiligen Rechteinhaber.

## Lizenz
Veröffentlicht unter der **MIT-Lizenz** (siehe Datei [`LICENSE`](./LICENSE)).
