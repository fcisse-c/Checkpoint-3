# Checkpoint 3
## Exercice 1

### Partie 1 : Gestion des utilisateurs
Configuration des utilisateurs (Windows Server)

Q.1.1.1 : Créer l'utilisateur Lionel Lemarchand avec les mêmes attributs que Kelly Rhameur
Connectez-vous à votre serveur Windows SRVWIN01.

Ouvrez l'outil Utilisateurs et ordinateur Active Directory (ADUC)

Localisez l'utilisateur Kelly Rhameur :

Cliquez droit sur son compte, puis choisissez Copier.

Remplissez les informations pour Lionel Lemarchand :

Nom d’utilisateur, prénom, mot de passe, etc.

Validez en cliquant sur Créer.
![image](https://github.com/user-attachments/assets/f3440880-44cc-45e1-b7f0-27318f457e21)

Q.1.1.2 : Créer une OU DeactivatedUsers et déplacer le compte désactivé de Kelly Rhameur dedans
Dans UOAD, faites un clic droit sur le domaine ou une autre OU existante.

Choisissez Nouvelle > Unité d'organisation (OU).

Nommez cette OU "DeactivatedUsers" et validez.

Désactivez le compte de Kelly Rhameur :
Clic droit sur son compte, puis Désactiver le compte.
![image](https://github.com/user-attachments/assets/2f69eddd-b76b-454f-893e-5b2ec446fe18)

Déplacez le compte vers "DeactivatedUsers" :

Faites un clic droit, sélectionnez Déplacer, et choisissez la nouvelle OU.
![image](https://github.com/user-attachments/assets/7b9e1c27-31c9-4ad0-8c03-eb741a2a42d2)


Q.1.1.3 : Modifier le groupe de l'OU dans laquelle était Kelly Rhameur
Toujours dans ADUC, localisez l'OU d'origine de Kelly Rhameur.
Sélectionnez les Propriétés de l'OU.

Accédez à l'onglet Groupes, puis ajoutez ou supprimez les groupes nécessaires.

Q.1.1.4 : Archiver le dossier de Kelly Rhameur et créer celui de Lionel Lemarchand
Accédez à l'emplacement des profils utilisateurs sur le serveur.
Compressez (archivez) le dossier de Kelly Rhameur, par exemple avec un outil comme ZIP.

Déplacez l’archive dans un emplacement sécurisé ou dédié pour l’archivage.

Créez un nouveau dossier pour Lionel Lemarchand, avec les mêmes permissions que Kelly Rhameur.

