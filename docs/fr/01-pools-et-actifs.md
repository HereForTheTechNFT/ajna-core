# 1. Pools et actifs

Ajna organise le credit autour de pools sans oracle externe ni gouvernance de taux. Chaque pool associe un quote token fourni par les preteurs a un collateral token apporte par les emprunteurs. Les fabriques distinguent les actifs ERC-20 et ERC-721, et les parametres de prix sont quantifies en buckets. Cette architecture rend le marche permissionless, mais reporte l evaluation du risque sur les participants. Les tokens a rebasing ou a frais de transfert peuvent produire des soldes incoherents et restent a eviter. Voir le code des fabriques et des pools dans src/.

[Chapitre suivant : buckets et liquidite](02-buckets-liquidite.md)
