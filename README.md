# Projecte Intermodular DAW - Plantilla de treball

Benvingut al repositori base per al projecte intermodular DAW. Aquest repositori serveix com a plantilla i punt de partida per a gestionar totes les tasques i entregues de manera organitzada i col·laborativa.

## Estructura de directoris

- `/bloc-1/`, `/bloc-2/`, ...: Carpetes que contenen les tasques agrupades per blocs.
- Cada tasca té la seva pròpia carpeta, per exemple `/bloc-1/tasca-1-1/` per a la Tasca 1.1.

## Com treballar en cada tasca

1. **Crear una nova branca específica per a la tasca**  
   Exemple:  

```bash
git checkout main
git pull origin main
git checkout -b feature/tasca1-1-investigacio-mercat
```

És imprescindible crear una branca nova per a cada tasca per mantenir l'organització i facilitar revisions.

2. **Desenvolupar i afegir els fitxers corresponents a la tasca**  
   Col·loca documents, codi o informes en la carpeta adequada:  
   `/bloc-x/tasca-x-x/`

3. **Fer commit dels canvis amb missatges clars**  
   Exemple:

```bash
git add .
git commit -m "Afegida la investigació de mercat per Tasca 1.1"
```

4. **Fer push a la branca remota**

``` bash
git push origin feature/tasca1-1-investigacio-mercat
```

5. **Crear una Pull Request (PR) cap a la branca `main`**
- Introdueix un títol descriptiu (ex: “Tasca 1.1 Investigació del mercat tecnològic”)
- Inclou una breu descripció amb l’estat de la tasca i continguts entregats.
- Assigna revisors (professor o equip).

6. **Esperar revisió i integrar la PR un cop aprovada.**

## Tauler Kanban de seguiment

Per gestionar l’estat de les tasques, utilitzarem el **Project Board** de GitHub amb les columnes:
- **Pendents**
- **En curs**
- **Revisió**
- **Finalitzat**

Cada issue o PR serà assignat a una columna segons l’estat actual.

## Bones pràctiques

- Treballar sempre en branques independents per a cada tasca.
- Fer commits petits, freqüents i amb missatges clars.
- Actualitzar l’estat de les issues i tasques al projecte Kanban.
- Seguir les indicacions i format de documents per mantenir la coherència.

## Recursos addicionals

Consulta el fitxer [guia-branques-commits-pr.md](docs/guia-branques-commits-pr.md) per a una guia detallada sobre l’ús de Git, branques, commits i PRs.
