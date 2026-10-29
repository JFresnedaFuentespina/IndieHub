# 05. Producte mínim viable (MVP)

## Objectiu de l'MVP

Desenvolupar una primera versió funcional d'IndieHub que permeti als desenvolupadors publicar i gestionar videojocs, i als jugadors descobrir-los, consultar-ne la informació i accedir-hi mitjançant la descàrrega o l'execució web compatible.

La proposta inicial contenia sis funcionalitats, que s'han agrupat en tres funcions principals per adaptar el projecte al temps i als recursos disponibles.

## F1. Gestió d'usuaris i publicació de videojocs

**Objectiu:** permetre que els desenvolupadors disposin d'un compte i puguin gestionar les seves publicacions.

Funcionalitats previstes:

- Registrar-se i iniciar sessió.
- Crear una publicació de videojoc.
- Incorporar-hi informació descriptiva, imatges i fitxers.
- Modificar les publicacions pròpies.
- Eliminar les publicacions pròpies.

Aquesta funció integra les funcionalitats 1 i 2 de la proposta inicial d'UT0.

## F2. Consulta del catàleg

**Objectiu:** facilitar que els jugadors trobin videojocs i n'obtinguin informació.

Funcionalitats previstes:

- Consultar el catàleg públic sense iniciar sessió.
- Cercar videojocs pel nom.
- Aplicar filtres bàsics.
- Accedir a una fitxa informativa de cada videojoc.

Aquesta funció integra les funcionalitats 3 i 4 de la proposta inicial d'UT0.

## F3. Accés i distribució dels videojocs

**Objectiu:** permetre que els jugadors accedeixin als videojocs publicats mitjançant diferents modalitats.

Funcionalitats previstes:

- Descarregar els fitxers dels videojocs.
- Executar al navegador els videojocs que disposin d'una build web compatible amb WebGL.
- Mostrar les opcions d'accés disponibles per a cada videojoc.

Aquesta funció correspon a la funcionalitat 5 de la proposta inicial d'UT0.

IndieHub no convertirà automàticament videojocs d'altres plataformes a WebGL. Els desenvolupadors hauran de proporcionar els fitxers adequats per a cada modalitat d'accés.

## Funcionalitats futures

Es reserven per a versions posteriors:

- Valoracions i comentaris.
- Sistema de favorits.
- Estadístiques de visites.
- Gestió avançada de versions.
- Perfils personalitzables.
- Recomanacions personalitzades.

## Criteri de finalització de l'MVP

L'MVP es considerarà funcional quan un desenvolupador pugui registrar-se i publicar un videojoc, quan els usuaris puguin consultar el catàleg i la fitxa informativa, i quan sigui possible descarregar els fitxers publicats o executar al navegador els videojocs que disposin d'una build WebGL compatible.