# 🧩 Components

Aquest document defineix els criteris que guien la creació i l'evolució dels components de la interfície de Straperla.

L'objectiu és construir una biblioteca de components coherent, reutilitzable i fàcil de mantenir, capaç d'evolucionar al mateix ritme que el producte.

---

## Principis

### Reutilització abans que creació

Abans de crear un component nou, es comprova si un component existent ja resol la necessitat.

La reutilització reforça la coherència de la interfície i simplifica el manteniment del sistema.

---

### Una única responsabilitat

Cada component ha de resoldre un únic problema.

Quan un component acumula massa responsabilitats, cal simplificar-lo o dividir-lo en components més petits.

---

### Consistència

Un mateix component manté sempre el mateix aspecte, comportament i significat.

Les variants només s'incorporen quan responen a una necessitat real del producte.

---

### Composició

Els components més complexos es construeixen combinant components més simples.

La composició afavoreix la reutilització, evita duplicacions i facilita l'evolució del sistema.

---

### Accessibilitat

Els components s'han de dissenyar perquè puguin ser utilitzats pel màxim nombre possible de persones.

L'accessibilitat forma part del component des del seu origen, no és una característica afegida posteriorment.

---

### Mobile First

Els components es defineixen primer per a dispositius mòbils.

Les adaptacions a pantalles més grans amplien les seves possibilitats, però no en modifiquen el comportament essencial.

---

## Organització del sistema

El sistema de components de Straperla s'estructura en quatre grans grups conceptuals:

### Components bàsics

Resolent les interaccions més elementals de la interfície.

Constitueixen la base sobre la qual es construeix la resta del sistema.

---

### Components de navegació

Faciliten el desplaçament de l'usuari per l'aplicació i mantenen una experiència coherent entre pantalles.

---

### Components d'interacció

Permeten que l'usuari introdueixi informació, executi accions o rebi resposta del sistema.

---

### Components de presentació

Organitzen i mostren la informació de manera clara, prioritzant sempre el contingut.

---

## Evolució

La biblioteca de components evoluciona a mesura que apareixen noves necessitats del producte.

Els components no es creen per preferències estètiques ni per casos puntuals, sinó quan aporten un benefici clar a la coherència, la reutilització o l'experiència d'usuari.

Cada nou component passa a formar part del sistema i ha de mantenir els mateixos criteris que la resta.

---

> *Un bon component resol un problema. Un bon sistema evita haver-lo de resoldre dues vegades.*