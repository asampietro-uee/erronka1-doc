---
layout: page
title: Datu-baseak
permalink: /datubase.html
---

# Datu-baseak

Atal honetan proiekturako sortutako eta erabilitako datu-basearen egitura eta kudeaketa deskribatzen da.

## 1. Datu-eredua (E-R Eredua)
- **Entitate nagusiak**: Erabiltzaileak, Produktuak, Eskaerak, etab.
- **Erlazioak**: Entitateen arteko kardinalitateak (1:1, 1:N, N:M).
- **Integritate-arauak**: Gako nagusiak (PK), kanpoko gakoak (FK) eta mugak (unique, not null).

## 2. Egitura eta Taulak
- SQL kontsulten bidez taulen sorrera (`CREATE TABLE`).
- Eremuen datu-motak eta luzerak egokituta (VARCHAR, INT, DATE, etab.).

## 3. SQL Eragiketak
- **CRUD eragiketak**: Insert, Select, Update, Delete.
- **Kontsulta aurreratuak**: JOIN eragiketak, agregazio-funtzioak (`COUNT`, `SUM`, `AVG`) eta taldekatzeak (`GROUP BY`, `HAVING`).

## 4. Segurtasuna eta Kudeaketa
- Segurtasun-kopiak (backup-ak) egitea eta leheneratzea.
- Erabiltzaileen baimenak eta rolak kudeatzea.
