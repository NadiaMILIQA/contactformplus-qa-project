## Cas de Test : TC002 - Email obligatoire

**Objectif** : Vérifier que le champ email est requis pour soumettre le formulaire.

**Préconditions** : Le formulaire ContactForm+ est affiché.

**Étapes de test** :
1. Laisser le champ Email vide
2. Remplir les autres champs valides
3. Cliquer sur le bouton "Envoyer"

**Données de test** :
- Nom : Dupont
- Prénom : Marie
- Email : (vide)
- Objet : Demande d’info
- Message : Bonjour

**Résultat attendu** : Un message d’erreur s’affiche indiquant que le champ email est obligatoire.
