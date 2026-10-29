# 07. Característiques inicials

## 1. Característiques funcionals

| ID | Característica | Necessitat relacionada | Funció de l'MVP |
|---|---|---|---|
| CF01 | Registre i inici de sessió. | N1 | F1 |
| CF02 | Creació, modificació i eliminació de publicacions pròpies. | N1, N2 | F1 |
| CF03 | Incorporació de la informació dels videojocs. | N1, N2 | F1 |
| CF04 | Consulta del catàleg de videojocs publicats. | N3 | F2 |
| CF05 | Cerca i filtratge bàsic dels videojocs. | N3 | F2 |
| CF06 | Visualització de la informació de cada videojoc. | N2, N3 | F2 |
| CF07 | Descàrrega dels fitxers dels videojocs. | N4 | F3 |
| CF08 | Execució de videojocs WebGL compatibles. | N5 | F3 |

## 2. Condicions tècniques

- El projecte disposarà d'un client, un servidor i un sistema de persistència de dades.
- La informació dels usuaris i dels videojocs s'emmagatzemarà en una base de dades relacional.
- Els fitxers dels videojocs s'emmagatzemaran per separat. La base de dades en conservarà les referències necessàries per gestionar-los.
- Inicialment es preveu utilitzar fitxers ZIP per publicar els videojocs.
- Per executar un videojoc al navegador, el desenvolupador haurà de proporcionar una build web compatible amb WebGL.
- IndieHub no convertirà automàticament videojocs d'altres plataformes a WebGL.
- El sistema haurà de gestionar la pujada, la validació, l'emmagatzematge, l'extracció quan sigui necessària i la distribució dels fitxers.
- La tecnologia concreta del client, del servidor i de l'emmagatzematge queda pendent de decisió.

## 3. Criteris de qualitat

| Criteri | Aplicació al projecte |
|---|---|
| Usabilitat | Publicació senzilla i navegació clara pel catàleg. |
| Seguretat | Protecció dels comptes i validació dels fitxers publicats. |
| Rendiment | Càrrega adequada del catàleg i dels videojocs web. |
| Compatibilitat | Funcionament als navegadors seleccionats i compatibilitat amb les builds web provades. |
| Integritat | Conservació correcta de la informació i dels fitxers associats. |
| Mantenibilitat | Organització del codi per facilitar les correccions i les ampliacions futures. |

## 4. Principal dificultat tècnica

La principal dificultat tècnica del projecte serà la gestió dels fitxers dels videojocs, especialment l'emmagatzematge, la validació, l'extracció i la distribució de les builds web.

Caldrà garantir que els fitxers es puguin servir correctament i que els videojocs compatibles s'executin des del navegador.

## 5. Decisions tècniques pendents

- Tecnologia definitiva del client.
- Tecnologia definitiva del servidor.
- Sistema de base de dades.
- Sistema d'emmagatzematge dels fitxers.
- Mida màxima permesa per als fitxers pujats.
- Formats acceptats per a la descàrrega.
- Procediment de validació i extracció dels fitxers ZIP.
- Navegadors i builds WebGL que es faran servir per a les proves.
- Mesures de seguretat per als continguts executables publicats per tercers.