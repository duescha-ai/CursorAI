# SAP Developer — своё дело в Германии + Cursor AI

**Полный пошаговый план.** Ориентир: первый проект через 2–4 месяца, стабильный поток через 6–9 месяцев.

---

## Содержание

1. [Фаза 0 — Подготовка (дни 1–14)](#фаза-0)
2. [Фаза 1 — Юридическая база (дни 15–45)](#фаза-1)
3. [Фаза 2 — Бизнес-инфраструктура (дни 30–60)](#фаза-2)
4. [Фаза 3 — Cursor AI + техстек (дни 14–45)](#фаза-3)
5. [Фаза 4 — Клиенты и продажи (дни 30–90)](#фаза-4)
6. [Фаза 5 — Первый проект (дни 60–120)](#фаза-5)
7. [Фаза 6 — Стабилизация (день 90+)](#фаза-6)
8. [Календарь: 30 / 60 / 90 дней](#календарь)
9. [Чеклисты и ошибки](#чеклисты)

---

## Фаза 0 — Подготовка (дни 1–14) {#фаза-0}

### Шаг 0.1 — Самооценка (день 1–2)

- [ ] Список навыков: ABAP, RAP, CDS, Fiori/UI5, BTP, CPI, S/4 migration, ECC legacy
- [ ] Выбрать 2–3 ниши (пример: «S/4 Clean Core extensions», «Fiori apps», «CPI integrations»)
- [ ] Уровень: Mid (70–90 €/h) или Senior (90–120 €/h)
- [ ] Языки клиентов: DE / EN / RU
- [ ] Модель: Vollzeit-Freelancer или Nebengewerbe (параллель с Arbeit)

### Шаг 0.2 — Финансовая подушка (день 2–3)

- [ ] 3–6 месяцев личных расходов в резерве
- [ ] Учесть: Krankenkasse ~400–800 €/мес, Steuerberater ~150–300 €/мес
- [ ] Цель дохода: 5–8k € брутто/мес → при 85 €/h ≈ 60–95 billable часов/мес

### Шаг 0.3 — Steuerberater (день 3–7)

- [ ] Найти: «Steuerberater Freiberufler IT [город]» или IHK-Empfehlung
- [ ] Termin buchen (Erstgespräch ~100–200 € или kostenlos)
- [ ] Вопросы:
  - Freiberufler (§18 EStG) или Gewerbe?
  - Kleinunternehmer (≤22k €/Jahr) или Regelbesteuerung?
  - Umsatzsteuer-Voranmeldung: monatlich oder quartalsweise?
  - Risiko Scheinselbständigkeit

### Шаг 0.4 — Scheinselbständigkeit (день 7)

**Не делать:**
- Один клиент, 100% Zeit, seine Tools, seine Kernarbeitszeiten, kein eigenes Risiko

**Делать:**
- Mehrere potenzielle Auftraggeber
- Eigenes Rechnungsmodell (Stunden/Projekt)
- Eigene Arbeitsmittel (Laptop, ADT)
- Werkvertrag mit klarer Leistungsbeschreibung

---

## Фаза 1 — Юридическая база (дни 15–45) {#фаза-1}

### Шаг 1.1 — Freiberufler vs Gewerbe (день 15)

| | Freiberufler | Gewerbe |
|--|--------------|---------|
| SAP Entwicklung / Beratung | Meist **ja** | Falls Finanzamt ablehnt |
| Gewerbeanmeldung | Oft **nicht** nötig | Gewerbeamt |
| Steuer | Einkommensteuer | + möglich Gewerbesteuer |

### Шаг 1.2 — Регистрация (день 15–20)

1. [ ] **Fragebogen zur steuerlichen Erfassung** (Finanzamt) — mit Steuerberater oder ELSTER
2. [ ] Falls nötig: **Gewerbeanmeldung** beim Gewerbeamt (~20–60 €)
3. [ ] Warten: **Steuernummer** (2–6 Wochen)
4. [ ] **USt-IdNr.** beantragen (für EU B2B, Reverse Charge)

### Шаг 1.3 — Geschäftskonto (день 18–25)

- [ ] N26 Business, Comdirect, Kontist, Holvi
- [ ] Keine privaten Ausgaben vom Geschäftskonto

### Шаг 1.4 — Firmenname (день 20)

- [ ] Einzelunternehmen: «Max Mustermann — SAP Development»
- [ ] Keine GmbH am Anfang (25k € Stammkapital, höhere Kosten)

---

## Фаза 2 — Бизнес-инфраструктура (дни 30–60) {#фаза-2}

### Шаг 2.1 — Страховки (день 25–35)

| Страховка | Pflicht? | Orientierung |
|-----------|----------|--------------|
| Krankenversicherung | **Ja** | GKV oder PKV |
| Berufshaftpflicht IT | **Empfohlen** | ~300–600 €/Jahr |
| Rechtsschutz | Optional | ~200–400 €/Jahr |

- [ ] Berufshaftpflicht: Deckung für Softwarefehler, Daten, Vermögensschaden
- [ ] KSK: für SAP meist **nicht** (nur künstlerische Berufe)

### Шаг 2.2 — Dokumente (день 30–40)

Vorlagen in `sap-freelancer-germany/templates/`:

- [ ] `rechnung-vorlage.md` — Rechnung
- [ ] `angebot-vorlage.md` — Projektangebot
- [ ] `werkvertrag-vorlage.md` — Werkvertrag
- [ ] `nda-vorlage.md` — Vertraulichkeit
- [ ] Mit Steuerberater final prüfen

### Шаг 2.3 — Buchhaltung (день 35–45)

- [ ] ELSTER-Zugang einrichten
- [ ] sevDesk, Lexoffice oder Steuerberater
- [ ] Jeden Monat: Einnahmen, Ausgaben, Belege sammeln
- [ ] USt-Voranmeldung fristgerecht

### Шаг 2.4 — Preise (день 40)

| Level | Stundensatz |
|-------|-------------|
| Mid ABAP | 70–90 €/h |
| Senior S/4, RAP | 90–120 €/h |
| BTP, CPI, Architekt | 100–130 €/h |

- [ ] Mindestpreis DE: **75 €/h**
- [ ] Tagessatz: 8 × Stundensatz

---

## Фаза 3 — Cursor AI + техстек (дни 14–45) {#фаза-3}

### Шаг 3.1 — Setup (день 14–16)

- [ ] Cursor Pro (langer Kontext, Cloud Agents)
- [ ] GitHub/GitLab für Portfolio (keine Kundendaten)
- [ ] Skill: `.cursor/skills/sap-freelancer-germany/SKILL.md`
- [ ] Rules: `.cursor/rules/sap-development.mdc`

### Шаг 3.2 — Datenschutz (день 16)

- [ ] **Keine** Produktivdaten in AI ohne NDA + DPA
- [ ] Synthetic/mock data für Demos
- [ ] Cursor Privacy Mode für Kunden-Repos
- [ ] Im Vertrag: AI nur auf anonymisiertem Code (optional)

### Шаг 3.3 — AI-Workflows (день 17–30)

| Aufgabe | Cursor |
|---------|--------|
| RAP/CDS neu | Spec → Code → Unit Tests |
| Legacy Report | Refactor-Plan → CDS → Tests |
| CPI iFlow | Mapping, Groovy, Error Handling |
| Doku | Code → technische Doku DE |
| Sprint | Tickets → Statusbericht DE/EN |
| Angebot | Scope → Angebot-Text |

### Шаг 3.4 — Portfolio (день 20–45, parallel)

**Showcase (1 auswählen):**

- **A)** CDS + RAP + Fiori Elements (Mock Sales Order)
- **B)** BTP CAP + OData + CPI Mock-Integration
- **C)** Migration Guide: ECC Report → CDS + Fiori (ohne Kundencode)

- [ ] Public GitHub Repo
- [ ] 1-seitige Case Study (DE/EN)
- [ ] LinkedIn-Post mit Link

### Шаг 3.5 — Qualität (immer)

- [ ] ADT Syntax Check
- [ ] ABAP Unit / Projekt-Tests
- [ ] Code Review vor Transport
- [ ] **Kein** AI-Code ohne menschliche Prüfung

---

## Фаза 4 — Клиенты и продажи (дни 30–90) {#фаза-4}

### Шаг 4.1 — LinkedIn (день 30–35)

- [ ] Headline: `Senior SAP Developer | S/4HANA RAP ABAP Fiori | Freelancer`
- [ ] About: Nische, Verfügbarkeit, Remote/Hybrid, Region
- [ ] Banner: Spezialisierung + «Projekte ab [Monat]»
- [ ] 3 Posts vor Start: Kase, Tech-Tipp, Verfügbarkeit

### Шаг 4.2 — Plattformen (день 35–42)

- [ ] [gulp.de](https://www.gulp.de)
- [ ] [freelancermap.de](https://www.freelancermap.de)
- [ ] [etengo.com](https://www.etengo.com)
- [ ] Profil DE + EN, Skills, Verfügbarkeit, Remote

### Шаг 4.3 — Netzwerk (день 40–60)

- [ ] 50 Ziel-Kontakte: SAP Partner Recruiter, ehemalige Kollegen, Projektleiter
- [ ] 3–5 Nachrichten pro Woche (persönlich, nicht Spam)
- [ ] SAP Partner: msg, All for One, NTT, lokale SAP-Häuser

### Шаг 4.4 — Elevator Pitch

> «Ich bin SAP Developer mit Fokus auf S/4HANA Clean Core — RAP, CDS, Fiori.  
> Als Freelancer unterstütze ich Mittelstand und Partner bei Extensions und Migration.  
> Verfügbar ab [Monat], remote oder hybrid in [Region].»

### Шаг 4.5 — Sales-Pipeline

| Stufe | SLA |
|-------|-----|
| Lead | Antwort < 24h |
| Erstgespräch | 30 Min: Projekt, Stack, Start |
| Angebot | Innerhalb 48h |
| Vertrag | Werkvertrag + NDA wenn nötig |
| Kick-off | Zugänge, Jira, Transport-Strategie |

### Шаг 4.6 — Agentur vs Endkunde

| | Agentur | Endkunde |
|--|---------|----------|
| Pro | Schneller Einstieg, weniger Sales | Höherer Satz, direkte Beziehung |
| Con | 10–20% weniger Satz | Längerer Sales-Zyklus |

---

## Фаза 5 — Первый проект (дни 60–120) {#фаза-5}

### Шаг 5.1 — Onboarding (Tag 1)

- [ ] VPN, ADT, SAP GUI, Jira, Confluence
- [ ] Namespace, Transportweg DEV→QA→PRD
- [ ] Definition of Done mit Team Lead

### Шаг 5.2 — Tagesablauf mit Cursor

```
08:30  Jira → Cursor: Priorität, Plan
09:00  Development (Code + Tests)
12:00  Standup (Update vorbereitet)
13:00  Review, Transport vorbereiten
16:00  Statusbericht, Ticket-Kommentare
17:00  Zeiterfassung (Toggl / Kunden-Tool)
```

### Шаг 5.3 — Abrechnung

- [ ] Monatsende: Rechnung (siehe Vorlage)
- [ ] Zahlungsziel 14–30 Tage
- [ ] Mahnung bei Überfälligkeit (14 Tage nach Fälligkeit)

### Шаг 5.4 — Referenz (Projektende)

- [ ] LinkedIn-Empfehlung
- [ ] Anonymisierte Case Study
- [ ] Post: «Verfügbar ab …»

---

## Фаза 6 — Стабилизация (день 90+) {#фаза-6}

### Шаг 6.1 — Ziele

- [ ] 120–160 billable Stunden/Monat
- [ ] 1 Langzeitprojekt (6+ Monate) oder 2 parallele
- [ ] 1 Retainer: 20h/Monat Support (~90 €/h)

### Шаг 6.2 — GmbH prüfen

- [ ] Mit Steuerberater ab ~60–80k € Gewinn/Jahr
- [ ] Alternative: UG (haftungsbeschränkt) mit 1k € Stammkapital

### Шаг 6.3 — Skalierung

- [ ] Website (Carrd, 1 Seite)
- [ ] Wiederkehrende Prozesse in Cursor Skills
- [ ] Optional: zweiter Freelancer als Partner (White-Label)

---

## Календарь {#календарь}

### 30 Tage — Tag für Tag

| Tag | Aktion |
|-----|--------|
| 1 | Skills-Liste, Finanzplan, Ziel-Stundensatz |
| 2 | Steuerberater recherchieren (5 Kandidaten) |
| 3 | Steuerberater-Termin buchen |
| 4 | Steuerberater-Gespräch |
| 5 | Freiberufler/Gewerbe Entscheidung |
| 6 | Fragebogen steuerliche Erfassung vorbereiten |
| 7 | Fragebogen absenden |
| 8 | Geschäftskonto beantragen |
| 9 | Berufshaftpflicht vergleichen (3 Anbieter) |
| 10 | Berufshaftpflicht abschließen |
| 11 | Krankenversicherung klären |
| 12 | Rechnungsvorlage anpassen |
| 13 | Werkvertrag mit Berater prüfen |
| 14 | Cursor Rules + Skill einrichten |
| 15 | LinkedIn Headline + About |
| 16 | LinkedIn Banner + 1. Post |
| 17 | Gulp Profil |
| 18 | freelancermap Profil |
| 19 | Portfolio-Repo anlegen |
| 20 | CDS + RAP Mock starten |
| 21 | Portfolio weiter |
| 22 | 10 Kontakte identifizieren |
| 23 | 5 Nachrichten senden |
| 24 | 5 Nachrichten senden |
| 25 | LinkedIn 2. Post (Tech) |
| 26 | Portfolio abschließen |
| 27 | Case Study schreiben (Cursor) |
| 28 | etengo Profil |
| 29 | Angebotsvorlage testen |
| 30 | Review: Legal-Status, Pipeline, Portfolio |

### 60 Tage — Meilensteine

- [ ] Steuernummer erhalten
- [ ] Erste Rechnung möglich (legal)
- [ ] Portfolio live
- [ ] 3+ aktive Gespräche mit Leads
- [ ] 30+ Netzwerk-Nachrichten gesendet

### 90 Tage — Meilensteine

- [ ] Erster Auftrag gestartet **oder** Angebot angenommen
- [ ] 80+ billable Stunden in einem Monat (Ziel)
- [ ] Retainer-Angebot an 1 Kunden gesendet
- [ ] Buchhaltung-Q1 ohne Fehler

---

## Чеклисты {#чеклисты}

### Vor jedem Projektstart

- [ ] Werkvertrag signiert
- [ ] NDA wenn nötig
- [ ] Stundensatz / Schätzung im Vertrag
- [ ] Zahlungsziel festgelegt
- [ ] Kein Scheinselbständigkeits-Risiko

### Vor jedem Transport

- [ ] Syntax Check
- [ ] Unit Tests grün
- [ ] Code Review
- [ ] Transport-Request dokumentiert

### Monatlich

- [ ] Zeiterfassung exportieren
- [ ] Rechnung senden
- [ ] Belege an Steuerberater / Tool
- [ ] Pipeline: 3 neue Kontakte

### Fehler vermeiden

1. Start ohne Steuerberater
2. Stundensatz < 65 €/h
3. Nur ein Kunde langfristig
4. Kundencode in AI ohne NDA
5. Keine Zeiterfassung
6. GmbH zu früh
7. AI-Code ohne Review in Produktion

---

## Cursor Prompts (Kopierliste)

**Angebot:**
```
Kunde: Mittelstand S/4HANA. Scope: 1 Fiori App Materialstamm, CDS+RAP, 80h.
Stundensatz 95€. Erstelle Angebot DE: Einleitung, Leistungen, Annahmen,
Zeitplan 10 Wochen, Zahlungsziel 14 Tage.
```

**Statusbericht:**
```
Sprint: CDS ZI_MATERIAL fertig, 2 Fiori-Bugs, Transport QA Freitag.
Statusbericht DE für Projektleiter, 1 Seite.
```

**RAP:**
```
Clean Core RAP managed: Entity ZI_SALES_ITEM, validations quantity>0,
material exists. ABAP 7.57, draft ZCL_TC_SALES_ITEM unit tests.
```

---

## Dateien in diesem Repo

| Pfad | Inhalt |
|------|--------|
| `MASTER-PLAN.md` | Dieser Plan |
| `templates/rechnung-vorlage.md` | Rechnung |
| `templates/angebot-vorlage.md` | Angebot |
| `templates/werkvertrag-vorlage.md` | Vertrag |
| `templates/nda-vorlage.md` | NDA |
| `templates/retainer-vorlage.md` | Retainer |
| `templates/linkedin-profil.md` | LinkedIn Texte |
| `templates/cursor-prompts.md` | Prompt-Bibliothek |
| `.cursor/skills/sap-freelancer-germany/SKILL.md` | Cursor Skill |
| `.cursor/rules/sap-development.mdc` | Cursor Rules |

**Steuerberater vor Nutzung der Vertragsvorlagen.**
