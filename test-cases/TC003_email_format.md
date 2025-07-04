## Cas de Test : TC003 - Format Email

**Objectif** : Vérifier que le champ email ne valide pas un format incorrect.

**Préconditions** : Le formulaire ContactForm+ est affiché.

**Étapes de test** :
1. Saisir une adresse email au mauvais format (ex: "test@")
2. Remplir les autres champs valides
3. Cliquer sur le bouton "Envoyer"

**Données de test** :
- Nom : Martin
- Prénom : Jean
- Email : test@
- Objet : Demande
- Message : Bonjour

**Résultat attendu** : Un message d’erreur s’affiche signalant que l’adresse email est invalide.
