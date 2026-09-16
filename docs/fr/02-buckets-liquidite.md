# 2. Buckets et liquidite

Un bucket represente un niveau de prix et conserve les depots de quote token ainsi que les parts LP correspondantes. Le preteur choisit donc une granularite de risque plutot qu un taux impose par une gouvernance. Les index de bucket, les arrondis et la liquidite disponible influencent la valeur d une position. Le LUP, ou Lowest Utilized Price, aide a lire la profondeur effectivement mobilisable par les emprunteurs. Un mauvais choix de bucket peut exposer le depot ou le collateral a une perte disproportionnee. Les appels d ajout et de retrait acceptent des limites pour proteger l intention utilisateur.

[Chapitre suivant : emprunt et dette](03-emprunt-dette.md)
