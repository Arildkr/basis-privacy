---
layout: default
title: Personvernerklæring — Basis
---

# Personvernerklæring for Basis

*Sist oppdatert: 24. mars 2026*

## 1. Om appen

Basis er en minimalistisk Android-launcher som erstatter telefonens startskjerm. Appen er utviklet av Arild Kristiansen.

## 2. Hvilke data samles inn

Appen samler ikke inn personopplysninger. Følgende data lagres lokalt på enheten:

- Liste over favorittapper (pakkenavn)
- Liste over arkiverte apper (pakkenavn)
- Temainnstillinger (farge, bakgrunn)
- Valgt sted for værvarsling (stedsnavn og koordinater)

## 3. Internettilgang

Appen henter værvarsler fra offentlig tilgjengelige API-er uten innlogging:

- **met.no** (Meteorologisk institutt) — værvarsler for valgt sted
- **Photon / Komoot** — stedsøk for å finne koordinater til værvarsling

Ingen personopplysninger sendes til disse tjenestene. Kun stedsnavn eller koordinater overføres.

## 4. Tillatelser

Appen bruker følgende Android-tillatelser:

| Tillatelse | Formål |
|---|---|
| `QUERY_ALL_PACKAGES` | Vise liste over installerte apper |
| `PACKAGE_USAGE_STATS` | Vise skjermtidsstatistikk |
| `INTERNET` | Hente værvarsler |

## 5. Lagring og sikkerhet

- All data lagres utelukkende lokalt på enheten via `SharedPreferences`
- Ingen data synkroniseres til sky eller deles med tredjeparter

## 6. Tredjepartsdata

Appen samler ikke inn analyse-, reklame- eller sporingsdata. Ingen tredjepartsbiblioteker for sporing er inkludert.

## 7. Sletting av data

All lokal data slettes ved å avinstallere appen eller tømme appdata via *Innstillinger → Apper → Basis → Tøm data*.

## 8. Endringer

Ved vesentlige endringer i denne erklæringen vil oppdatert versjon bli gjort tilgjengelig på denne siden.

## 9. Kontakt

Spørsmål om personvern kan rettes til: arild@fravaer.no
