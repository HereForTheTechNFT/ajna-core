# 5. Positions et factories

Les fabriques deployent les pools ERC-20 ou ERC-721 et la PositionManager encapsule des positions de liquidite. Les NFT de position rendent la propriete transferible, mais une vente sur un marche ouvert peut etre front-run : le vendeur peut retirer la position avant le transfert. Les contrats d utilite exposent des vues et des multicalls pour reconstruire les soldes, les buckets et la dette. La precision des decimales, le taux de change et les arrondis peuvent modifier la valeur d une part LP. Une interface serieuse doit afficher ces donnees brutes et refuser les montants ambigus.

[Chapitre suivant : limites et perimetre](06-limites-perimetre.md)
