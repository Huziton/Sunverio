# Sunverio Digital — weboldal

Statikus weboldal. Nincs build, nincs függőség: elég a fájlokat kiszolgálni.

## Fájlok

| | |
|---|---|
| `index.html` | főoldal — bemutatkozás, munkák, GYIK, kapcsolati űrlap |
| `szolgaltatasok.html` | szolgáltatások részletesen |
| `arak.html` | árlista, havi díjas konstrukció, karbantartás |
| `jogi.html` | impresszum és adatkezelési tájékoztató |
| `kepek/` | logó, szalagképek, előnézeti képek, megosztási kép |
| `robots.txt`, `sitemap.xml`, `llms.txt` | keresőknek és AI-asszisztenseknek |
| `.nojekyll` | GitHub Pages: ne dolgozza fel Jekyllel |

## GitHub Pages

Repository → **Settings → Pages → Source: Deploy from a branch → main / (root)**.
Pár perc múlva él a cím.

## Ami cserére vár

**1. A domain.** Az `og:` megosztási címkék, a `canonical`, a `sitemap.xml` és a
`robots.txt` a `https://demo.kovacspenzugy.hu` címre mutat. Ha máshol lesz az oldal,
ezt a címet kell mindenhol lecserélni a valódira.

**2. Az impresszum.** A `jogi.html` jelenleg azt írja, hogy a bejegyzés folyamatban van.
A vállalkozói nyilvántartásba vétel után be kell írni a nevet, a nyilvántartási számot,
az adószámot és a székhelyet.

**3. Az e-mail cím.** Az oldalon a `kapcsolat@sunverio.hu` szerepel. Amíg ez a postafiók
nem él, a levelek nem érkeznek meg — a kapcsolati űrlap viszont működik (Formspree).
