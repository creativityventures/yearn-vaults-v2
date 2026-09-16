# 4. Rapports, rendement et frais

Le rapport périodique d’une stratégie synchronise sa dette, ses gains réalisés, ses pertes et les frais dus au protocole. Le coffre utilise ces informations pour mettre à jour la valeur des parts et maintenir une comptabilité cohérente entre capital disponible et capital investi.

Les frais peuvent rémunérer la performance ou le fonctionnement, dans les limites configurées par la gouvernance. Le mécanisme de récolte doit préserver la protection contre les gains artificiels et tenir compte du dernier rapport accepté. Les scénarios correspondants sont documentés dans tests/functional/strategy/test_fees.py et les tests de pertes.

[Chapitre suivant : arrêt d’urgence et limites](05-safety.md).
