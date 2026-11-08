# AradExperience

**Arad, într-o singură aplicație.** Evenimente și bilete, ghid audio la obiective, hartă cu transportul în comun live, oferte de la localurile din oraș și o comunitate în care faptele bune aduc puncte. Construită în două zile la **Hack4Arad 2026**.

*Arad in one app: events and tickets, audio guides, live public transport, local offers and a community that earns points. Built in two days at Hack4Arad 2026.*

**Încearc-o:** [aradexperience.site](https://aradexperience.site), apoi **„Intră ca vizitator”**, fără cont și fără cod.

## Ce face

- **Asistent AI**: îi spui „am 4 ore, pe jos, istorie și o cafea” și primești traseul, cu ore, hartă și opriri reale din Arad.
- **Evenimente și bilete** în aplicație, cu cod QR care merge și offline; plata cu cardul (Stripe, în modul de test).
- **Ghid audio** la Cetatea Aradului, Palatul Cultural și celelalte obiective.
- **Transport în comun** CTP Arad cu vehiculele live pe hartă și planificator de drum.
- **Comunitate**: acțiuni pentru oraș (plantări, curățenie, donări), validate de Primărie cu un cod QR; punctele se cheltuie la cafenelele și magazinele partenere.
- **Panouri web** pentru Primărie, firme și administrare.

## Cum e construită

| Repo | Ce e |
|---|---|
| [AradEx-Frontend](https://github.com/HACK4ARAD/AradEx-Frontend) | Vue 3 · Vite · Tailwind: site-ul cu panourile și aplicația mobilă (Capacitor, Android + iOS) |
| [AradEx-Backend](https://github.com/HACK4ARAD/AradEx-Backend) | Spring Boot 3 · Java 21 · PostgreSQL 16, Claude API pentru asistent, Stripe pentru plăți |
| [AradEx-Infrastructure](https://github.com/HACK4ARAD/AradEx-Infrastructure) | producția pe AWS în Terraform: ECS Fargate, RDS, S3, Route 53, Secrets Manager |
| [AradEx-Ops](https://github.com/HACK4ARAD/AradEx-Ops) | gateway-ul de SMS pentru codurile de login (Mac + iPhone) |
| [AradEx-Plan](https://github.com/HACK4ARAD/AradEx-Plan) | planul, contractul API, modelul de date, designul și documentația |

## Echipa

[ZOCZELI](https://github.com/ZOCZELI) · [LukasL2004](https://github.com/LukasL2004) · [vaidaoctav](https://github.com/vaidaoctav) · [DamAndrei04](https://github.com/DamAndrei04)

<sub>Pozele obiectivelor: Wikimedia Commons (CC BY / CC BY-SA), autorii în [AradEx-Plan/design](https://github.com/HACK4ARAD/AradEx-Plan/tree/main/design).</sub>
