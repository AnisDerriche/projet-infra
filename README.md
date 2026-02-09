# 🏗️ Projet Niveau 3 : Infrastructure Professionnelle
> **Déploiement, Supervision, Maintenance & Documentation**

[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![Context](https://img.shields.io/badge/Company-B2Tech_Solutions-blue.svg)]()
[![Time](https://img.shields.io/badge/Durée-40h-orange.svg)]()

## 📋 Description du Projet

| Niveau | Pré-requis | Description |
| :---: | :---: | :--- |
| **1** | - | Mise en place de base (LAMP) |
| **2** | Niv. 1 | Services avancés (OwnCloud, DHCP, DNS, Sécu) |
| **3** | **Niv. 1 + 2** | **Automatisation, Supervision & Maintenance (Ce projet)** |

---

## 👥 Binômes & Objectifs
*Liste des binômes et niveau minimum engagé :*

| Binôme | Niveau Choisi |
| **AD / MD** | Niv. 3 |

---

## 🏢 Contexte d’Entreprise : B2Tech Solutions

Suite à la mise en place du serveur LAMP (**Projet 1**) et des services OwnCloud/DHCP/DNS sécurisés (**Projet 2**), **B2Tech Solutions** souhaite professionnaliser son infrastructure interne.

La DSI vous confie la création d’un environnement de production **complet**, capable d'être :
* 🚀 **Déployé et configuré automatiquement**
* 👀 **Surveillé en continu**
* 🛠️ **Maintenu selon un plan structuré**
* 📚 **Documenté de manière professionnelle**

Ce projet simule la mise en place d’une infrastructure durable, conforme aux **bonnes pratiques industrielles**.

---

## 📅 Planning du Projet
### 1. Socle Technique & Reprise de l'existant

Reprise intégrale des travaux des Projets 1 et 2 pour obtenir un socle stable :
- [X] Serveur Linux opérationnel
- [X] Stack LAMP fonctionnelle
- [x] OwnCloud configuré
- [x] DHCP et DNS opérationnels
- [x] Serveur entièrement sécurisé

#### 2.2 Configuration et Scripting
Création de scripts/recettes/playbooks pour automatiser :
- [x] Création utilisateurs & mots de passe
- [x] Configuration de la sécurité
- [x] Installation des paquets
- [x] Personnalisation de configurations (ex: `apache2.conf`, `my.cnf`)
- [x] **Test :** Déploiement automatisé d'une application de test.

#### 3 Outils de surveillance
* **Outils suggérés :** Nagios, Zabbix, Netdata, Prometheus (au choix).
* **Objectifs :** Monitorer CPU, RAM, Disque, Services.
* **Actions :** Mise en place d'alertes et simulation d'incidents (arrêt service, surcharge).

#### 3.1 Plan de maintenance & Sauvegardes
* Rédiger un plan de maintenance (tâches journalières/hebdos/mensuelles).
* Mettre en place des **sauvegardes automatiques** (Données, Configs, Fichiers critiques).
* **Crash Test :** Simuler une perte de données et effectuer une restauration.

### 4. Documentation Technique

Rédaction d'une documentation professionnelle pour le technicien futur :
* 📄 Description des composants.
* 💻 Extraits de fichiers de conf & commandes.
* 🤖 Procédures de déploiement auto.
* 🛡️ Stratégie de supervision & maintenance.
* 🖼️ Illustrations (Captures, schémas d'archi).

---

## ✅ Contraintes de la DSI

Le projet doit impérativement respecter les points suivants :

1.  **Légalité & Sécurité :** Respect RGPD, sécurité système, segmentation logique.
2.  **Automatisation Réelle :** Pas de scripts fictifs, l'outil de déploiement doit être fonctionnel.
3.  **Temps Réel :** La supervision doit être active.
4.  **Résilience :** Les sauvegardes doivent être **testées** et fonctionnelles.
5.  **Clarté :** Documentation exploitable en situation pro.

---
