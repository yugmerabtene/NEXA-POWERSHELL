# 📘 **Syllabus complet – Cours PowerShell avec travaux pratiques**

## 🔹 **Introduction à PowerShell & commandes de base**

### 🧠 Contenu théorique :
- Présentation de PowerShell et son positionnement
- Différences entre CMD, Bash et PowerShell
- PowerShell Core vs Windows PowerShell
- Cmdlets, syntaxe de base, pipelines
- Aide intégrée (`Get-Help`, `Get-Command`, `Get-Member`)
- Variables, types de données, opérateurs
- Formatage et redirection (table, liste, CSV, JSON)

### 💻 Travaux pratiques :
- Utiliser `Get-Help` et `Get-Command` pour documenter des cmdlets
- Manipuler des variables et afficher leurs types
- Lister les processus/services avec filtrage (`Where-Object`)
- Exporter des résultats dans différents formats (CSV, JSON)

---

## 🔹 **Structures de contrôle & gestion de fichiers**

### 🧠 Contenu théorique :
- Structures conditionnelles : `if`, `elseif`, `else`, `switch`
- Boucles : `for`, `foreach`, `while`, `do`
- Fonctions, paramètres, blocs `begin`, `process`, `end`
- Gestion des erreurs avec `try`, `catch`, `finally`
- Parcourir l’arborescence d’un système de fichiers
- Manipulation des dates, chaînes de caractères, expressions régulières

### 💻 Travaux pratiques :
- Créer un script qui classe les fichiers d’un dossier selon leur extension
- Écrire un script de sauvegarde basé sur la date et taille des fichiers
- Implémenter des fonctions réutilisables avec gestion des erreurs

---

## 🔹 **Gestion des processus, services, utilisateurs et tâches planifiées**

### 🧠 Contenu théorique :
- Gérer les processus (`Get/Start/Stop-Process`)
- Gérer les services Windows (`Get/Start/Restart/Stop-Service`)
- Lire et écrire dans le registre Windows
- Créer, modifier, supprimer des comptes utilisateurs locaux
- Créer et gérer des tâches planifiées (`schtasks`, `ScheduledTasks`)

### 💻 Travaux pratiques :
- Script de surveillance et redémarrage automatique de processus critiques
- Auditer et documenter tous les services actifs
- Script de création automatisée d’utilisateurs avec mot de passe complexe
- Planifier un nettoyage automatique du disque avec `schtasks`

---

## 🔹 **Scripting avancé & sécurité**

### 🧠 Contenu théorique :
- Définir des paramètres avec contraintes (`param()`, `ValidateSet`, etc.)
- Organisation en modules (`.psm1`, `Import-Module`)
- Signature numérique des scripts
- Politiques d’exécution (`Get/Set-ExecutionPolicy`)
- Gestion sécurisée des identifiants (`SecureString`, `PSCredential`)
- Journalisation, historique, logs personnalisés

### 💻 Travaux pratiques :
- Créer un module contenant plusieurs fonctions métiers
- Signer un script avec un certificat auto-généré
- Script de connexion à distance sécurisé (PowerShell Remoting)
- Script d’audit système avec journalisation personnalisée

---

## 🔹 **Administration système avec PowerShell (AD, Réseau, Azure, DevOps)**

### 🧠 Contenu théorique :
- PowerShell et Active Directory (module RSAT, gestion des utilisateurs/groupes/OU)
- Requêtes LDAP et filtrage avancé
- Cmdlets réseau (`Test-Connection`, `Resolve-DnsName`, `Get-NetTCPConnection`)
- Introduction à PowerShell avec Azure (`Az` module)
- Intégration avec DevOps : scripts de déploiement, templates

### 💻 Travaux pratiques :
- Script de nettoyage d’utilisateurs inactifs dans Active Directory
- Script de test réseau complet (ping, DNS, ports, débit)
- Simulation de déploiement d’une VM Azure (ou version locale simulée)
- Génération automatique d’un dashboard HTML de monitoring système

---

## 🔹 **Évaluation finale (optionnelle mais recommandée)**

### 💡 Projet global :
> **Créer un script d’audit automatique d’un poste ou serveur Windows incluant :**
> - Informations système (RAM, CPU, disques)
> - État des services critiques
> - Liste des utilisateurs, groupes, tâches planifiées
> - Rapport généré en HTML ou CSV avec timestamp
