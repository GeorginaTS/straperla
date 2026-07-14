# 🗂️ Information Architecture

Aquest document defineix com s'organitza la informació dins de Straperla.

L'objectiu és facilitar que les persones descobreixin productes i productors de proximitat de la manera més senzilla possible.

L'arquitectura de la informació ha de respondre a les necessitats de les persones abans que a les funcionalitats del sistema.

---

# Principis

* La descoberta és el punt de partida.
* La proximitat determina la rellevància.
* El producte és la porta d'entrada.
* El productor aporta el context i genera confiança.
* La informació ha de ser fàcil de trobar i d'entendre.
* Cada pantalla ha de tenir un objectiu clar.

---

# Estructura principal

```
Inici
├── Cerca
├── Categories
├── Productes de proximitat
└── Accés al mapa

Mapa

Favorits

Perfil
```

---

# Inici

La pantalla principal és el punt d'entrada a Straperla.

Ha de permetre descobrir ràpidament productes de proximitat sense necessitat de registrar-se.

## Contingut

* Presentació breu de Straperla.
* Cercador.
* Categories.
* Productes de proximitat.
* Accés al mapa.

La presentació ocupa la part superior de la pantalla i es redueix quan l'usuari comença a desplaçar-se.

---

# Cerca

La cerca és el principal mecanisme per trobar informació.

Permet cercar simultàniament:

* Productes.
* Productors.

Les categories actuen com a filtres ràpids per facilitar la descoberta.

---

# Producte

El producte és la unitat principal de descoberta.

Cada fitxa ha de mostrar la informació essencial per ajudar l'usuari a decidir si vol contactar amb el productor.

## Informació principal

* Fotografia.
* Nom.
* Productor.
* Distància.
* Municipi.
* Descripció.
* Contacte.

Només es mostren productes disponibles.

---

# Productor

Cada productor disposa d'una fitxa pròpia.

L'objectiu és generar confiança i donar context als productes que ofereix.

## Informació principal

* Fotografia.
* Nom.
* Descripció.
* Municipi.
* Productes disponibles.
* Contacte.

La ubicació es mostra a nivell de municipi per preservar la privacitat.

---

# Mapa

El mapa és una eina d'exploració.

Complementa la navegació principal, però no n'és el punt d'entrada.

Permet descobrir productes i productors sobre el territori.

---

# Favorits

Permet desar productors i productes d'interès.

En el futur podrà facilitar el seguiment de novetats dels productors preferits.

---

# Perfil

Existeixen dos tipus de perfil.

## Consumidor

Perfil privat.

Permet gestionar les preferències, els favorits i les converses.

## Productor

Permet gestionar:

* Perfil.
* Productes.
* Disponibilitat.
* Contactes.

---

# Relacions

```
Producte
    │
    ▼
Productor
    │
    ▼
Altres productes
```

La descoberta acostuma a començar en un producte, però continua coneixent la persona o el projecte que hi ha al darrere.

---

> *L'arquitectura de Straperla no s'organitza per funcionalitats, sinó per facilitar la descoberta de les petites perles que tenim a prop.*
