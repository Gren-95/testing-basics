# Test Plan for Web Application
Version: 1.0
Date: 2024-03-19
Author: QA Team

## 1. Pealkiri, versioon, autorid
- **Projekti nimi:** Web Application Testing Project
- **Versioon:** 1.0
- **Autorid:** QA Team
- **Kuupäev:** 2024-03-19

## 2. Dokumendi ajalugu ja heakskiidud
| Versioon | Kuupäev | Autor | Muudatused |
|----------|---------|-------|------------|
| 1.0 | 2024-03-19 | QA Team | Esialgne versioon |

**Heakskiitjad:**
- QA Lead: [Nimi] - [Kuupäev]
- Project Manager: [Nimi] - [Kuupäev]

## 3. Eesmärk ja ulatus
### Eesmärk
Selle testplaani eesmärk on tagada veebirakenduse kvaliteet läbi süstemaatilise testimise protsessi, mis hõlmab nii manuaalset kui automatiseeritud testimist.

### Ulatus
Testimine hõlmab:
- Kasutajaliidese funktsionaalsust
- Andmebaasi operatsioone
- API integratsioone
- Jõudlust ja skaleeritavust
- Turvalisust

## 4. Viited ja alusdokumendid
- IEEE 829-2008 standard
- ISO/IEC/IEEE 29119-3:2013
- Projekti nõuded (JIRA/Confluence)
- UI/UX disainid (Figma)
- API dokumentatsioon (Swagger)

## 5. Testitavad üksused
- Frontend komponendid
- Backend API-d
- Andmebaasi operatsioonid
- Autentimis- ja autoriseerimissüsteem
- Integratsioonid kolmandate osapoolte teenustega

## 6. Testitavad ja mittetestitavad omadused
### Testitavad omadused
- Kasutajaliidese funktsionaalsus
- Andmebaasi operatsioonid
- API integratsioonid
- Autentimine ja autoriseerimine
- Andmete valideerimine

### Mittetestitavad omadused
- Kolmandate osapoolte teenuste sisemine loogika
- Infrastruktuuri konfiguratsioon
- Deployment protsess

## 7. Testimise lähenemine
### Meetodid
- Funktsionaalne testimine
- Integratsioonitestimine
- Jõudlustestimine
- Turvalisuse testimine
- Kasutajakogemuse testimine

### Tööriistad
- Playwright (E2E testimine)
- Jest (Ühiktestimine)
- Postman (API testimine)
- Lighthouse (Jõudlustestimine)
- OWASP ZAP (Turvalisuse testimine)

## 8. Sisenemis-, väljumis- ja peatamiskriteeriumid
### Sisenemiskriteeriumid
- Testkeskkond on valmis
- Testandmed on olemas
- Testjuhtumid on valmis
- Testimise tööriistad on paigaldatud

### Väljumiskriteeriumid
- Kõik kriitilised testid on läbitud
- Avatud defektid on lahendatud või dokumenteeritud
- Testraportid on valmis

### Peatamiskriteeriumid
- Kriitilised defektid blokeerivad testimist
- Testkeskkond on ebastabiilne
- Testandmed on vigased

## 9. Ressursid ja rollid
### Inimesed
- QA Lead
- Test Engineerid
- DevOps Engineer
- Backend Developer
- Frontend Developer

### Tarkvara
- Node.js
- Playwright
- Jest
- Postman
- Docker

### Riistvara
- Test serverid
- CI/CD pipeline
- Monitoring tööriistad

## 10. Ajakava ja verstapostid
### Sprint 1 (2 nädalat)
- Testplaan valmis
- Testjuhtumid valmis
- Automatiseeritud testide alus

### Sprint 2 (2 nädalat)
- E2E testid automatiseeritud
- API testid automatiseeritud
- Jõudlustestid valmis

## 11. Keskkond ja infrastruktuur
### Testkeskkonnad
- Development
- Staging
- Production

### Infrastruktuur
- Docker konteinerid
- CI/CD pipeline
- Monitoring süsteemid

## 12. Testide disaini viited
- [Manual Test Cases](./testcases/)
- [Automated Tests](../automation/)
- [Test Data](./testdata/)

## 13. Riskid ja leevendused
| Risk | Tõenäosus | Mõju | Leevendus |
|------|-----------|------|-----------|
| Testkeskkonna ebastabiilsus | Keskmine | Kõrge | Redundantne keskkond |
| Andmete kvaliteet | Keskmine | Keskmine | Andmete valideerimine |
| Ajaressursside puudus | Kõrge | Kõrge | Prioriteetide seadmine |

## 14. Luba- ja auditeerimisnõuded
- GDPR nõuetele vastavus
- ISO 27001 standard
- Andmete privaatsuse tagamine
- Audit logide säilitamine

## 15. Testi töövoo protseduurid
### Defekti elutsükkel
1. Defekti avastamine
2. Dokumenteerimine
3. Prioriteedi määramine
4. Lahendamine
5. Verifitseerimine
6. Sulgemine

### Muudatuste kontroll
- Kõik muudatused peavad läbima code review
- Testid peavad läbima enne merge'it
- Dokumentatsioon peab olema ajakohane

## 16. Mõõdikud ja raportid
### KPI-d
- Testide katvus
- Defektide tihedus
- Testide läbimise aeg
- Automatiseerimise tase

### Aruannete sagedus
- Igapäevased testi raportid
- Nädalased kokkuvõtted
- Kuu lõpu ülevaated

## 17. Lõpuleviimise kriteerium ja hooldus
### Lõpuleviimise kriteeriumid
- Kõik kriitilised testid on läbitud
- Avatud defektid on lahendatud
- Dokumentatsioon on ajakohane

### Hooldus
- Testjuhtumite regulaarne uuendamine
- Automatiseeritud testide hooldus
- Dokumentatsiooni ajakohastamine

## 18. Testjuhtumite loetelu
Testjuhtumid asuvad kaustas [tests/manual/testcases/](./testcases/):
- TC-001: Kasutaja autentimine
- TC-002: Andmete lisamine
- TC-003: Andmete muutmine
- TC-004: Andmete kustutamine
- [Jne...]

## 19. Test-run'i raportid
Test-run'i raportid asuvad kaustas [reports/](../../reports/):
- testrun_2024-03-19.md
- [Järgmised raportid...] 