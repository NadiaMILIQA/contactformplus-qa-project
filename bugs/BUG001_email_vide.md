## Bug : BUG001 - Message envoyé sans adresse email

**Contexte** : Le formulaire autorise l’envoi même si le champ Email est laissé vide.

**Étapes pour reproduire** :
1. Laisser le champ Email vide
2. Remplir les autres champs
3. Cliquer sur "Envoyer"

**Résultat observé** :  
Le message est envoyé sans aucune validation du champ Email.

**Résultat attendu** :  
Le formulaire devrait afficher une erreur indiquant que le champ Email est obligatoire.

**Gravité** : Haute  
**Cas de test lié** : TC002 - Email obligatoire
