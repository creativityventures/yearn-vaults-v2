# 2. Parts, dépôts et valorisation

Lors d’un dépôt, le coffre transforme l’actif reçu en parts proportionnelles à la valeur totale déjà gérée. Le ratio dépend du total des actifs, des parts en circulation et des fonds temporairement indisponibles dans les stratégies. Un retrait brûle les parts et restitue l’actif selon le même prix, avec des limites lorsque la liquidité immédiate ne suffit pas.

Les protections de parts et de prix sont essentielles : elles évitent qu’un appel externe, une perte déclarée ou un arrondi ne crée une émission injustifiée. Les tests de tests/functional/vault/test_shares.py et test_withdrawal.py donnent les scénarios de référence à relire.

[Chapitre suivant : stratégies et allocation](03-strategies.md).
