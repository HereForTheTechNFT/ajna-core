# 4. Liquidations et recuperation

Quand une position devient liquidatable, le protocole permet a un liquidateur de prendre du collateral contre du quote token selon la courbe de prix de la pool. Les actions kick et take organisent la mise en vente et la prise du collateral, avec des callbacks proteges par nonReentrant. La disponibilite de plusieurs acteurs fait partie de l hypothese economique : un marche desert peut permettre une acquisition a prix tres faible. Les timestamps et la disponibilite de la chaine participent aussi au calcul. Les interfaces d integration doivent donc gerer les limites de prix, le slippage et les echecs de callback.

[Chapitre suivant : positions et factories](05-positions-factories.md)
