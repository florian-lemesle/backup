Dans cette branche, vous aller supprimer tout le contenu du Readme
et le remplacer par la présentation,avec vos mots,
de 6 commandes Git vues en cours ou que vous utilisez régulièrement.
Vous expliquerez notamment à quel moment cette commande peut servir.

Voici la liste des 6 commandes:

git add permet d'ajouter les modification faites en local pour les préparer à les envoyer en remote
git commit -m git commit fait un "snapshot" de l'état du repo local avec les modifications apportés avec git add
git push envoie ce qu'on a  commit vers le repo distant
git fetch permet de vérifier si des modifs ont été faite sur le repo distant par rapport à notre repo local
git pull permet de récupérer les fichiers modifiés du repo distant en local
git merge git merge permet de fusionner deux branche par exemple avec le main

comment protéger une branche dans Gitlab ?
Pour protéger une branche dans GitLab, je dois d'abord accéder aux paramètres de mon dépôt.
Ensuite, je navigue vers la section des paramètres du dépôt et je choisis la branche que je veux protéger.
Une fois sélectionnée, je coche la case pour la marquer comme protégée, puis je configure les permissions,
selon mes besoins, comme l'interdiction de suppression ou la restriction de fusion.
Enfin, je sauvegarde les modifications pour les appliquer. Une fois que la branche est protégée,
seuls les utilisateurs autorisés pourront effectuer certaines actions sur cette branche,
conformément aux permissions que j'ai définies.

pourquoi protéger des branches dans Git ?

Protéger des branches dans Git est essentiel pour maintenir la qualité et la stabilité du code dans un projet. 
En empêchant des actions telles que la suppression accidentelle ou la fusion non autorisée de modifications, 
la protection des branches garantit l'intégrité du code source.Cela permet de réduire les risques d'erreurs et de conflits
en assurant que seuls les contributeurs autorisés peuvent effectuer des opérations critiques sur les branches protégées.
De plus, cela favorise une gestion efficace du flux de travail, en facilitant la collaboration et en assurant une traçabilité claire des modifications apportées au code.

qu'est ce qui peut entraîner des merge conflicts et comment les résoudre ?

Les conflits de merge surviennent lorsque différentes parties du code sont modifiées de manière incompatible par différents contributeurs.
Pour les résoudre, je dois examiner les zones de conflit, choisir quelles modifications conserver et finaliser la fusion en marquant les conflits comme résolus dans Git.
