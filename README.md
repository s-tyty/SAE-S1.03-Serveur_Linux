# Mise en place d'un Poste de Développement & Serveur Web (SAÉ S1.03)

Ce projet documente la mise en place d'un environnement de travail Linux complet et le déploiement d'un site web, réalisés dans le cadre du BUT Informatique.

## Architecture Technique

* **Virtualisation :** VirtualBox
* **OS :** Ubuntu (Linux)
* **Serveur Web :** Apache2
* **Ressources de la VM :** 4 vCPU, 4 Go de RAM, 80 Go de stockage dynamique.

## Tâches Réalisées

1. **Installation de l'OS :** Configuration d'une VM Ubuntu avec gestion des utilisateurs et des groupes (`sudo groupadd`, `usermod`).
2. **Personnalisation :** Modification du fichier `.bashrc` pour une invite de commande personnalisée.
3. **Administration :** Installation des Additions Invité (*Guest Additions*) et gestion des paquets (`apt`).
4. **Déploiement Web :** Installation d'Apache2 et transfert manuel des fichiers du site vers `/var/www/html` via le terminal.

## Le Site Web

Le site présente le rapport d'installation et répond aux questions techniques concernant la virtualisation (Différences entre Émulateur/Simulateur/Virtualisation, Hyperviseurs de Type 1 & 2, etc.).

*Technologies : HTML5 / CSS3 / Bootstrap 5*.
