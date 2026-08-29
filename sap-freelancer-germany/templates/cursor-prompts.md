# Cursor Prompts — SAP Freelancer Bibliothek

## Entwicklung

### RAP managed scenario
```
Clean Core RAP managed scenario for entity ZI_SALES_ORDER_ITEM.
Fields: sales_order, item, material, quantity, net_amount.
Validations: quantity > 0, material must exist in I_Material.
Draft determination if header status is open.
ABAP 7.57, namespace ZDEV. Include draft class ZCL_TC_SALES_ITEM.
```

### CDS View
```
Create CDS view ZI_MATERIAL_STOCK with:
- Material, plant, storage location, stock quantity
- Association to I_Material and I_Plant
- Access control via PFCG if standard pattern exists
- Annotation for Fiori list report
```

### Legacy refactor
```
Analyze this ABAP report snippet. Propose refactor plan:
1) Extract data access to CDS
2) Business logic to ZCL_* class
3) ABAP Unit tests for calculations
No modifications to standard. Output: step list + draft CDS + class skeleton.
```

### Fiori Elements
```
RAP OData service ZUI_MATERIAL_O4 already exists.
Generate Fiori Elements app manifest structure: List Report + Object Page.
Fields: material, description, plant, stock. German UI labels.
```

### CPI iFlow
```
SAP Cloud Integration: map IDoc MATMAS to REST JSON.
Error handling: retry 3x, dead letter log.
Groovy mapping for material number padding to 18 chars.
Document assumptions in comments.
```

---

## Dokumentation

### Technische Doku (DE)
```
Erstelle technische Dokumentation DE für:
- CDS ZI_MATERIAL, RAP BO ZI_MATERIAL, Fiori App ZUI_MATERIAL
Sections: Zweck, Architektur, Transporte, Berechtigungen, Tests, Bekannte Einschränkungen.
Zielgruppe: SAP Basis + Entwickler.
```

### Statusbericht Sprint (DE)
```
Sprint 12 Statusbericht DE für Projektleiter:
- Fertig: CDS ZI_MATERIAL, RAP validations, Fiori LR
- In Arbeit: Object Page custom fields
- Blocker: QA transport Berechtigung
- Plan nächste Woche: QA transport, 2 Bugfixes
- Risiko: Scope Change Anfrage zusätzliche Felder (+8h)
Ton: professionell, 1 Seite.
```

### Ticket-Kommentar (EN)
```
Jira comment EN for developers:
Implemented ZBP_I_SALES_ITEM validation for quantity.
Unit tests ZCL_TC_SALES_ITEM passing in DEV.
Ready for review — transport DEVK9... requested.
```

---

## Business (DE)

### Angebot
```
Kunde: Mittelstand, S/4HANA 2023.
Scope: Fiori App Materialdisposition, CDS+RAP+Fiori Elements, 80h Schätzung.
Stundensatz 95€, remote, Start 01.10.
Erstelle vollständiges Angebot DE mit Scope, Annahmen, Zeitplan 10 Wochen, Zahlungsziel 14 Tage.
```

### Change Request
```
Kunde möchte zusätzlich 5 Felder auf Object Page (+PDF Export).
Ursprungsangebot 80h. Schätze Mehraufwand, formuliere Change Request E-Mail DE:
höflich, sachlich, Stunden + Kosten, neue Gesamtschätzung.
```

### Mahnung
```
Rechnung 2026-008 über 18.088€, Fälligkeit 14.08, heute 29.08 unpaid.
Formuliere erste Zahlungsaufforderung DE — freundlich aber klar, Frist 7 Tage.
```

---

## Review / Qualität

### Code Review Checklist
```
Review this ABAP class for:
Clean Core compliance, performance (SELECT in loop), 
error handling, unit test coverage, naming Z-namespace,
security (no hardcoded auth bypass).
Output: findings P1/P2/P3 + suggested fixes.
```

### Transport checklist
```
Generate transport release checklist for:
CDS ZI_MATERIAL, ZBP_I_MATERIAL, ZUI_MATERIAL_O4, Fiori app.
Include: object list, import order, regression tests, rollback note.
```

---

## Portfolio

### Case Study
```
Write anonymized case study EN for portfolio website:
Client: manufacturing Mittelstand, S/4HANA 2022.
Project: replaced Z legacy report with RAP + Fiori Elements.
Results: 40% faster user workflow, Clean Core compliant.
No client name. 300 words, professional tone.
```
