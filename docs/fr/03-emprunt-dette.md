# 3. Emprunt et dette

L emprunteur depose son collateral puis tire du quote token dans les limites de la pool. La dette, le prix de liquidation et les facteurs de risque sont calcules a partir des buckets utilises, sans prix fourni par un oracle. Les fonctions de drawDebt et repayDebt mettent a jour les engagements et les index de liquidite. Les bornes de prix et de temps ne sont pas decoratives : elles evitent qu un acteur ou un bot deplace la liquidite juste avant l operation. La pool ne permet pas de tirer une dette dans le meme bloc que sa creation. Les integrations doivent donc verifier les retours et les limites avant chaque transaction.

[Chapitre suivant : liquidations](04-liquidations.md)
