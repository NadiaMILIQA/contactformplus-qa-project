## Bug : BUG002 - Aucun message d’erreur pour un email invalide

**Contexte** : Le formulaire accepte des emails au format incorrect (ex : "test@", "abc").

**Étapes pour reproduire** :
1. Saisir un email invalide dans le champ Email
2. Remplir les autres champs avec des données valides
3. Cliquer sur "Envoyer"

**Résultat observé** :  
Le formulaire est envoyé sans erreur malgré un email invalide.

**Résultat attendu** :  
Une erreur doit apparaître pour signaler que l’adresse email est incorrecte.

**Gravité** : Moyenne  
**Cas de test lié** : TC003 - Format email
