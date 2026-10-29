# 08. Registre de decisions

Aquest document recull les decisions inicials del projecte, les qüestions pendents i els criteris que s'hauran de seguir per mantenir coherent el desenvolupament d'IndieHub.

## 1. Decisions preses

### D01. Nom del projecte
**Decisió:** el projecte s'anomena IndieHub.

### D02. Tipus de producte
**Decisió:** serà una plataforma web orientada a la publicació, la descoberta, la descàrrega i l'execució web de videojocs independents.

### D03. Perfils principals
**Decisió:** els perfils principals són desenvolupadors independents i jugadors. Un mateix usuari podrà fer servir la plataforma amb totes dues finalitats.

### D04. Abast de l'MVP
**Decisió:** les sis funcionalitats inicials s'agrupen en tres funcionalitats principals:
- F1. Gestió d'usuaris i publicació de videojocs.
- F2. Consulta i descoberta del catàleg.
- F3. Accés i distribució de videojocs.

### D05. Descàrrega de videojocs
**Decisió:** la descàrrega dels fitxers dels videojocs forma part de l'MVP.

### D06. Execució al navegador
**Decisió:** l'execució de builds web compatibles forma part de l'MVP. No es generarà automàticament una versió web a partir d'un build d'escriptori.

### D07. Valoracions i comentaris
**Decisió:** les valoracions i els comentaris no formen part de l'MVP. Es consideraran per a una versió futura.

### D08. Abast realista
**Decisió:** es prioritzaran els fluxos essencials abans d'afegir funcionalitats avançades de comunitat, distribució o gestió de descàrregues.

## 2. Decisions tècniques pendents

| ID | Qüestió | Motiu | Criteri per decidir |
|---|---|---|---|
| P01 | Quin framework s'utilitzarà al client? | Condiciona l'estructura de la interfície. | Experiència de l'equip, temps i requisits del projecte. |
| P02 | Quina tecnologia s'utilitzarà al servidor? | Ha de gestionar usuaris, publicacions i fitxers. | Coneixements de l'equip, mantenibilitat i facilitat d'integració. |
| P03 | Quina base de dades s'utilitzarà? | Cal persistir comptes i metadades. | Relacions entre dades, facilitat de desenvolupament i recursos disponibles. |
| P04 | On s'emmagatzemaran els fitxers? | Els videojocs poden ocupar molt espai. | Cost, capacitat, seguretat i facilitat de desplegament. |
| P05 | Quins formats s'acceptaran? | La descàrrega i l'execució web tenen requisits diferents. | Compatibilitat real i resultats de les proves. |
| P06 | Quina mida màxima tindran els fitxers? | Cal limitar l'ús d'emmagatzematge i ample de banda. | Recursos disponibles i proves de càrrega. |
| P07 | Com s'aïllaran els builds web? | Els videojocs publicats poden incloure codi de tercers. | Seguretat del navegador i separació respecte de la plataforma. |

## 3. Supòsits de treball

- La plataforma permetrà publicar videojocs independents.
- Les publicacions inclouran metadades i fitxers associats.
- La descàrrega i l'execució web són modalitats diferents d'accés.
- L'execució web dependrà de l'existència d'un build compatible.
- Les característiques avançades no es consideraran obligatòries si no s'han aprovat com a part de l'MVP.

## 4. Criteri de gestió de canvis

Si l'equip modifica una decisió, haurà d'actualitzar aquest document i els documents de context afectats.

Les decisions s'han de distingir dels supòsits i de les qüestions pendents. Una tecnologia o funcionalitat no es considerarà confirmada fins que l'equip n'hagi acordat explícitament la selecció.

## 5. Historial

| Data | Canvi | Estat |
|---|---|---|
| 2026-10-29 | Definició inicial de l'MVP i registre de decisions. | Inicial |