# Utilisation du hook commitInfo.txt

Ce hook permet d'ajouter des informations supplémentaires sur un commit

# Pour l'utiliser, voici la démarche à suivre :

1 - Place toi sur ce chemin `.git/hooks`
2 - Renomme le fichier pre-commit.sample par pre-commit avec la commande `cp pre-commit.sample pre-commit`
3 - Rend le script exécutatble en utilisant la commande `chmod +x .git/hooks/pre-commit`
4 - Lorsque tu effectura un commit, vous serez invité à ajouter des informations de commit automatiquement
Une question te sera posé, répond `y` pour ajouter la date et l'heure de vérification du commit dans le fichier `suivi/commitInfo.txt`