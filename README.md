# 🏗️ Projet Niveau 3 : Infrastructure Professionnelle
> **Déploiement, Supervision, Maintenance & Documentation**

[![Status](https://img.shields.io/badge/Status-Active-success.svg)]()
[![Context](https://img.shields.io/badge/Company-B2Tech_Solutions-blue.svg)]()
[![Time](https://img.shields.io/badge/Durée-40h-orange.svg)]()

## 📋 Description du Module

Ce cours se déroulera sous la forme d'un projet à réaliser en **binôme**, avec trois niveaux de difficulté progressifs.

| Niveau | Pré-requis | Description |
| :---: | :---: | :--- |
| **1** | - | Mise en place de base (LAMP) |
| **2** | Niv. 1 | Services avancés (OwnCloud, DHCP, DNS, Sécu) |
| **3** | **Niv. 1 + 2** | **Automatisation, Supervision & Maintenance (Ce projet)** |

> **Règle de progression :** Si vous choisissez le niveau 3, vous devez valider les niveaux 1 et 2. Les acquis sont cumulatifs.

---

## 👥 Binômes & Objectifs
*Liste des binômes et niveau minimum engagé :*

| Binôme | Niveau Choisi | Remarques |
| :--- | :---: | :--- |
| **[Nom 1] / [Nom 2]** | Niv. X | ... |
| **[Nom 3] / [Nom 4]** | Niv. X | ... |
| **DEF** | ... | ... |

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

## 📅 Planning du Projet (40 Heures)

### 1. Socle Technique & Reprise de l'existant
⏱️ **Temps estimé : 15 heures**

Reprise intégrale des travaux des Projets 1 et 2 pour obtenir un socle stable :
- [ ] Serveur Linux opérationnel
- [ ] Stack LAMP fonctionnelle
- [ ] OwnCloud configuré
- [ ] DHCP et DNS opérationnels
- [ ] Serveur entièrement sécurisé

### 2. Déploiement Automatisé
⏱️ **Temps estimé : 8 heures**

#### 2.1 Choix et installation (3h)
* **Comparer** les solutions (Ansible, Chef, Puppet...).
* **Choisir** l'outil le plus adapté (simplicité, maintenance, documentation).
* **Installer** l'outil sur le serveur.

#### 2.2 Configuration et Scripting (5h)
Création de scripts/recettes/playbooks pour automatiser :
- [ ] Création utilisateurs & mots de passe
- [ ] Configuration de la sécurité
- [ ] Installation des paquets
- [ ] Personnalisation de configurations (ex: `apache2.conf`, `my.cnf`)
- [ ] **Test :** Déploiement automatisé d'une application de test.

### 3. Supervision & Maintenance
⏱️ **Temps estimé : 8 heures**

#### 3.1 Outils de surveillance (4h)
* **Outils suggérés :** Nagios, Zabbix, Netdata, Prometheus (au choix).
* **Objectifs :** Monitorer CPU, RAM, Disque, Services.
* **Actions :** Mise en place d'alertes et simulation d'incidents (arrêt service, surcharge).

#### 3.2 Plan de maintenance & Sauvegardes (4h)
* Rédiger un plan de maintenance (tâches journalières/hebdos/mensuelles).
* Mettre en place des **sauvegardes automatiques** (Données, Configs, Fichiers critiques).
* **Crash Test :** Simuler une perte de données et effectuer une restauration.

### 4. Documentation Technique
⏱️ **Temps estimé : 9 heures**

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

## 📢 Rendu Final & Soutenance

Pour valider ce niveau, le rendu comprend une exigence de présentation :

> **🎯 Format du rendu :**
> * Une **Présentation PowerPoint** structurée.
> * Une **Démonstration Fonctionnelle (POC)** sur machine.
> * **Durée totale :** 20 minutes.
