# 3. Stratégies et allocation du capital

Une stratégie reçoit une allocation du coffre et expose ses capacités, sa dette et son dernier rapport. Le coffre ajuste la dette, accepte les profits, comptabilise les pertes et peut retirer les fonds selon les règles de migration. Le modèle sépare la logique d’investissement de la comptabilité du coffre.

Les rôles de gouvernance contrôlent l’ajout, la révocation et la mise à jour des stratégies. Les contrôles d’état empêchent une stratégie inactive ou en urgence de recevoir du capital. Les fichiers de contracts/BaseStrategy.sol et les tests du dossier tests/functional/strategy/ sont les points d’entrée du mécanisme.

[Chapitre suivant : rapports et frais](04-reports.md).
