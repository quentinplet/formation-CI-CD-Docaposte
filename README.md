# formation-CI-CD-Docaposte

Pour tester le workflow de merge, il faut faire une pull request et la merger. 
Le workflow se lance lorsque la pull request est fermée (closed) et vérifie si elle a été mergée (merged). Si c'est le cas, il affiche un message de confirmation.

Ensuite pour tester le worflow suivant, il sera déclenché après le workflow de lerge, et affichera un message de confirmation que la PR a été mergée avec succès, ainsi que des détails sur la PR (titre, auteur, branches source et cible).