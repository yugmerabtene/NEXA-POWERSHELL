# 📘 **Syllabus Complet – PowerShell**

---

## 🔸 **PARTIE 1 – Bases de PowerShell**

### 🧠 Contenu :
- Présentation de PowerShell (historique, contextes d’usage)
- PowerShell Core vs Windows PowerShell
- Cmdlets : structure, nommage, principe de verb-noun
- Pipelines et traitement séquentiel
- Aide intégrée (`Get-Help`, `Get-Command`, `Get-Member`)
- Variables, types de données, opérateurs logiques et arithmétiques
- Redirection et formats d’affichage (table, liste, CSV, JSON)

### 💻 TP :
- Explorer l’aide PowerShell et documenter des cmdlets
- Créer et manipuler des variables typées
- Lister les processus actifs avec filtrage, tri et export CSV

---

## 🔸 **PARTIE 2 – Structures de contrôle & gestion des fichiers**

### 🧠 Contenu :
- Structures conditionnelles (`if`, `switch`)
- Boucles (`for`, `foreach`, `while`, `do`)
- Fonctions et paramètres (`param()`)
- Gestion des erreurs : `try`, `catch`, `finally`
- Parcours de répertoires, gestion de fichiers
- Manipulation des chaînes, dates, et expressions régulières

### 💻 TP :
- Script qui parcourt un dossier et classe les fichiers par extension
- Script de sauvegarde avec conditions sur la taille/date
- Fonctions réutilisables avec gestion d’erreur

---

## 🔸 **PARTIE 3 – Gestion système locale : processus, services, utilisateurs, tâches**

### 🧠 Contenu :
- Cmdlets pour les processus (`Get/Start/Stop-Process`)
- Gestion des services Windows (`Get/Start/Stop/Restart-Service`)
- Lecture/écriture dans le registre
- Gestion d’utilisateurs et groupes locaux (`New-LocalUser`, `Add-LocalGroupMember`)
- Tâches planifiées (`ScheduledTasks`, `schtasks.exe`)

### 💻 TP :
- Script de redémarrage automatique d’un processus critique
- Audit de l’état des services avec export CSV
- Création d’utilisateurs et attribution de droits locaux
- Script de planification de maintenance quotidienne

---

## 🔸 **PARTIE 4 – Scripting avancé, sécurité et modules**

### 🧠 Contenu :
- Paramètres de script avec contraintes (`param`, `ValidateSet`, `Mandatory`)
- Organisation modulaire (`.psm1`, `Export-ModuleMember`)
- Signature de scripts (certificats, politiques d’exécution)
- Gestion sécurisée des mots de passe (`SecureString`, `ConvertFrom-SecureString`)
- Connexions distantes (`Invoke-Command`, `Enter-PSSession`)
- Journalisation et logging personnalisé

### 💻 TP :
- Créer un module de fonctions métiers réutilisables
- Signer et exécuter un script sécurisé
- Créer un script d’audit avec logs et mots de passe chiffrés
- Exécution d’un script sur une machine distante (simulée ou réelle)

---

## 🔸 **PARTIE 5 – Administration avancée : Active Directory, Réseau, Azure, DevOps**

### 🧠 Contenu :
- Gestion d’Active Directory (module RSAT)
  - Utilisateurs, groupes, unités d’organisation
  - Recherches LDAP, filtrage avec `Where-Object`
- Cmdlets réseau (`Test-Connection`, `Resolve-DnsName`, `Get-NetTCPConnection`)
- Introduction à Azure avec PowerShell (`Az` module)
- Automatisation DevOps (déploiement, gestion de configuration, intégration CI/CD)

### 💻 TP :
- Script d’audit AD : détecter les comptes inactifs
- Script de test réseau complet (connectivité, ports, DNS)
- Déploiement simulé de ressources Azure
- Générer un tableau de bord HTML de monitoring système

---

## 🔸 **PARTIE 6 – Projet final : Audit système automatisé**

### 💡 Objectif :
Créer un **script complet d’audit de poste/serveur** avec :
- Informations système : RAM, CPU, disques
- Services critiques actifs
- Comptes utilisateurs locaux ou AD
- Liste des tâches planifiées
- Résultat formaté (CSV, JSON ou HTML)
