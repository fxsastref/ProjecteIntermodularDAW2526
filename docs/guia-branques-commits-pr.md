# Guia d’ús de Git: Branques, commits i Pull Requests (PR)

## Crear una branca nova

```bash

git checkout main
git pull origin main
git checkout -b feature/nova-tasca

```

## Fer canvis i addicionar-los

```

git add <fitxers_modificats>
git commit -m "Missatge clar i descriptiu del canvi"

```

## Enviar els canvis a GitHub

```

git push origin feature/nova-tasca

```

## Crear un Pull Request (PR)

- Des de GitHub, crea un nou PR des de la branca `feature/nova-tasca` cap a la branca `main`.
- Escriu un títol descriptiu.
- Explica què conté la PR, l’estat i qualsevol detall útil.
- Assigna revisors per fer la comprovació.

## Missatges de commit recomanats

- “Afegida la implementació de ...”
- “Corregit error a ...”
- “Actualitzada documentació de ...”

Mantingues-los curts i descriptius.
