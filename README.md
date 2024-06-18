# Algorithme d'Allocation de Mémoire par Pire Ajustement (Worst-Fit)

## Introduction

L'algorithme d'allocation de mémoire par pire ajustement est une technique de gestion de la mémoire dynamique qui consiste à attribuer la mémoire en trouvant le plus grand bloc de mémoire disponible qui est suffisant pour la demande. Cette approche laisse souvent de grands blocs de mémoire libres, ce qui peut être utile pour de futures demandes de mémoire plus importantes.

## Fonctionnement

### Étapes de l'Algorithme

1. **Initialiser les blocs de mémoire et les demandes d'allocation :** Définir les blocs de mémoire disponibles et les demandes d'allocation.
2. **Trouver le plus grand bloc libre :** Pour chaque demande, trouver le plus grand bloc de mémoire libre qui peut satisfaire la demande.
3. **Allouer la mémoire :** Si un bloc approprié est trouvé, allouer la mémoire et marquer le bloc comme utilisé. Sinon, indiquer que l'allocation a échoué.
4. **Afficher les résultats :** Afficher l'état final des blocs de mémoire après toutes les allocations.

## Exemple en Python

Voici un exemple de code Python implémentant l'algorithme d'allocation de mémoire par pire ajustement.

### Définition des Blocs de Mémoire et des Demandes

```python
# Définir les blocs de mémoire avec leurs tailles (initialement tous sont libr
objets = [417, 426 , 220, 112]
bacsMax = 3
taillebacs = 500