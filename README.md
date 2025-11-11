# Projet Minitrice - Groupe 8

## Table des matières
- [Installation](#installation)
- [Exécution](#exécution)
- [Références](#références)

## Installation
- Python 3 requis
- Rendre les scripts exécutables : chmod +x minitrice generator

## Exécution
- Mode interactif : python minitrice
- Mode pipe : echo "3+5" | python minitrice
- Génération aléatoire : python generator 5 | python minitrice
- Résultats tests : 
for f in test/*.txt; do
    python minitrice < "$f" > results/$(basename "$f" .txt)-result.txt
done

## Références
- [Python docs](https://docs.python.org/3/)
- learngitbranching.js.org
- https://rogerdudler.github.io/git-guide/index.fr.html
