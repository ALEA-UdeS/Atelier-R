# Atelier R

**Formateur:** Jean-Philippe Morissette

## Première journée d'atelier

- [Présentation HTML](https://ALEA-UdeS.github.io/Atelier-R/Atelier_1A)


## Séance 2: Introduction au language R

- [Présentation HTML](https://econumuds.github.io/BIO109/cours2)

## Séance 3: Les fonctions

- [Présentation HTML](https://econumuds.github.io/BIO109/cours3)

## Séance 4: Algorithmique I

- [Présentation HTML](https://econumuds.github.io/BIO109/cours4)

## Séance 5: Algorithmique II

- [Présentation HTML](https://econumuds.github.io/BIO109/cours5)

# Prise en main

### Compiler toutes les présentations

```bash
bash _build.sh
```

### Compiler une seule présentation

```bash
cd cours5/
Rscript -e "rmarkdown::render('index.Rmd')"
```


### Utilisation du diaporama

### Taille écran:

  - `F` pour basculwer en plein écran,
  - zoom du navigateur pour ajuster la taille de la présentation (typiquement `cmd +/-`),
  - `W` pour basculer en mode "large".

### Naviguer entre diapo

  - `G` pour entrer le numéro d'une slide,
  - `O` pour naviguer facilement dans la présentation,
  - `T` pour avoir une barre avec le numéro des diapositive.

# Exporter en format pdf

- Utiliser l'exportation pdf du navigateur,
- Utiliser [Decktape](https://github.com/astefanutti/decktape).
