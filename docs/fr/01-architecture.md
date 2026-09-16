# 1. Architecture des coffres Yearn v2

Yearn v2 organise le rendement autour d’un coffre ERC-20 qui émet des parts en échange d’un actif sous-jacent. Le coffre conserve les soldes, calcule la valeur par part et délègue le capital à des stratégies spécialisées. La séparation entre coffre, stratégie, registre et gouvernance rend le parcours lisible et permet de remplacer une stratégie sans déplacer la relation avec le déposant.

Le dépôt décrit aussi un modèle de stratégie réutilisable, des scripts d’exploitation et une suite de tests fonctionnels. Cette documentation suit les contrats et la SPECIFICATION.md du dépôt.

[Chapitre suivant : parts et valorisation](02-shares.md).
