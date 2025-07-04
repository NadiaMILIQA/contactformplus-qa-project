# Rapport d’Exécution des Tests – ContactForm+

## Résumé
Les cas de test ont été exécutés manuellement sur le formulaire ContactForm+. Résultat global : 2 réussis / 2 bloqué (bug).

## Détail des cas de test

| ID     | Titre                          | Statut   | Observations                     |
|--------|--------------------------------|----------|----------------------------------|
| TC001  | Envoi message valide           | ✅ Passé |                                  |
| TC002  | Email obligatoire              | ❌ Échoué| BUG001 : Absence de message d’erreur |
| TC003  | Format email invalide          | ❌ Échoué| BUG002 : Le champ accepte un mauvais format |
| TC004  | Réinitialisation du formulaire | ✅ Passé |                                  |

## Conclusion
Des anomalies critiques ont été remontées sur la validation du champ email. Des corrections sont à prévoir avant mise en production.
