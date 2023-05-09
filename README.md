# Projet-B1-Infra-SI

# Projet de simulation de réseau d'entreprise sur VirtualBox

Ce projet vise à simuler un réseau d'entreprise en utilisant VirtualBox, en mettant en place des serveurs Debian pour les rôles de serveur Web et de serveur de sauvegarde, un routeur pfSense pour assurer la sécurité et la gestion du trafic, et des clients Ubuntu et Windows pour représenter les postes de travail des employés.

## Objectifs

- Créer et configurer un réseau d'entreprise réaliste à des fins de formation
- Mettre en pratique les compétences en administration réseau et systèmes
- Expérimenter avec différentes solutions techniques pour répondre aux besoins de l'entreprise

## Architecture du réseau

Le réseau se compose des éléments suivants :

1. Serveur Web (Debian) : Héberge le site Web de l'entreprise
2. Serveur de Sauvegarde (Debian) : Sauvegarde les données du serveur Web toutes les 24 heures
3. Routeur pfSense : Gère le trafic réseau et assure la sécurité avec un pare-feu
4. Client Ubuntu : Représente un poste de travail Linux dans l'entreprise
5. Client Windows : Représente un poste de travail Windows dans l'entreprise

## Documentation

Le répertoire `docs/` contient la documentation technique détaillée pour la création et la configuration du réseau d'entreprise simulé. Les étapes décrites dans la documentation couvrent :

- Installation de VirtualBox
- Création des machines virtuelles
- Configuration du réseau
- Installation et configuration du routeur pfSense
- Installation et configuration des serveurs Debian et des clients Ubuntu et Windows
- Configuration du serveur Web et du serveur de sauvegarde
- Test des clients et de la connectivité réseau
- Validation et documentation

## Comment contribuer

N'hésitez pas à contribuer en soumettant des pull requests avec des améliorations, des corrections de bugs ou des suggestions pour de nouvelles fonctionnalités.

## Licence

Ce projet est distribué sous la licence MIT. Voir le fichier `LICENSE` pour plus d'informations.
