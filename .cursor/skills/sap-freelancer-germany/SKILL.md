---
name: sap-freelancer-germany
description: >-
  SAP Developer Freelancer in Germany: business setup, ABAP/RAP/Fiori/BTP development,
  client acquisition, invoicing, contracts (DE), Cursor AI workflows.
  Triggers: SAP freelancer, SAP Freiberufler, своё дело SAP, ABAP freelance Germany,
  S/4HANA freelancer, Cursor SAP, отпуск SAP разработчик, SAP Nebengewerbe.
---

# SAP Freelancer Germany + Cursor AI

Помогай с **своим делом SAP Developer в Германии** и с **разработкой с Cursor AI**.

## Языки

RU, DE, EN — отвечай на языке последнего сообщения пользователя.

## Два режима работы

### A) Бизнес (Freelancer)

Регистрация, Steuerberater, Versicherung, Preise, Kunden, Verträge, Rechnungen, Scheinselbständigkeit.

Шаблоны: `sap-freelancer-germany/templates/`
План: `sap-freelancer-germany/MASTER-PLAN.md`

### B) Entwicklung (SAP + Cursor)

ABAP, RAP, CDS, Fiori, BTP, CPI — с правилами Clean Core.

Rules: `.cursor/rules/sap-development.mdc`

## Жёсткие правила разработки

1. **Clean Core** — extensions only (Z/Y namespace), keine Modifications
2. **ABAP 7.57+**, RAP bevorzugt wo möglich
3. Naming: `ZI_*` CDS, `ZCL_*` classes, `ZR_*` reports
4. Unit tests für Business Logic
5. **Keine** Produktivdaten, Mandanten, Kundennamen in AI-Kontext
6. AI-Code immer: Syntax Check + Review vor Transport

## Stundensätze (Orientierung DE 2025–2026)

| Level | €/h |
|-------|-----|
| Mid | 70–90 |
| Senior S/4/RAP | 90–120 |
| BTP/CPI/Architekt | 100–130 |

Mindestpreis DE: 75 €/h.

## Sales-Pipeline SLA

| Stufe | Zeit |
|-------|------|
| Lead-Antwort | < 24h |
| Angebot nach Call | < 48h |
| Kick-off nach Vertrag | wie vereinbart |

## Typische Cursor-Workflows

1. **Spec → RAP**: CDS view → behavior → service → Fiori stub → unit tests
2. **Legacy**: Report snippet → refactor plan → CDS extraction → tests
3. **Doku**: Code → technische Doku DE
4. **Business**: Scope bullets → Angebot DE
5. **Sprint**: Ticket-Liste → Statusbericht DE/EN

## Scheinselbständigkeit — Warnsignale

Отклонять или mit Steuerberater prüfen wenn:
- Nur ein Auftraggeber, 100% Auslastung
- Feste Kernarbeitszeiten wie Angestellter
- Kein eigenes Rechnungsmodell
- Weisungsgebunden ohne eigenes Risiko

## Bei Fragen «план шаг за шагом»

Открыть `MASTER-PLAN.md`, указать текущую фазу и следующие 3 конкретные шаги с чекбоксами.

## Portfolio-Empfehlung

Ein public Showcase: CDS + RAP + Fiori Elements (mock), ohne Kundendaten.
