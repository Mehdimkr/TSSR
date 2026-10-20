# 🪟 Windows Cheat Sheet : raccourcis, .cpl, .msc et commandes

> Lancer une commande : `Win + R` (Exécuter), CMD ou PowerShell.
> Certaines commandes demandent les droits administrateur, ou une édition Pro/Entreprise (notée *Pro+*).

## Sommaire

1. [Raccourcis touche Windows](#1-raccourcis-touche-windows-)
2. [Autres raccourcis clavier](#2-autres-raccourcis-clavier)
3. [Panneau de configuration : .cpl](#3-panneau-de-configuration--cpl)
4. [Consoles de gestion : .msc](#4-consoles-de-gestion--msc)
5. [Outils et commandes (autres)](#5-outils-et-commandes-autres)
6. [Commandes réseau et système (CMD)](#6-commandes-réseau-et-système-cmd)
7. [Dossiers spéciaux et URI](#7-dossiers-spéciaux-et-uri)

---

## 1. Raccourcis touche Windows (⊞)

### Bases

| Raccourci | Action |
|-----------|--------|
| `Win` | Ouvrir le menu Démarrer |
| `Win + D` | Afficher / masquer le Bureau |
| `Win + E` | Explorateur de fichiers |
| `Win + R` | Exécuter |
| `Win + L` | Verrouiller la session |
| `Win + I` | Paramètres |
| `Win + X` | Menu utilisateur avancé (Gestionnaire de périphériques, Terminal…) |
| `Win + S` ou `Win + Q` | Recherche |
| `Win + A` | Paramètres rapides (Wi-Fi, luminosité…) |
| `Win + N` | Centre de notifications / calendrier (Windows 11) |
| `Win + W` | Widgets (Windows 11) |
| `Win + Pause` | Propriétés système / À propos |

### Fenêtres et bureaux

| Raccourci | Action |
|-----------|--------|
| `Win + Tab` | Vue des tâches (bureaux virtuels) |
| `Win + ↑ / ↓` | Agrandir / réduire la fenêtre |
| `Win + ← / →` | Ancrer la fenêtre à gauche / droite |
| `Win + Shift + ← / →` | Déplacer la fenêtre vers un autre écran |
| `Win + Z` | Dispositions d'ancrage (Windows 11) |
| `Win + M` | Réduire toutes les fenêtres |
| `Win + Shift + M` | Restaurer les fenêtres réduites |
| `Win + Home` | Réduire toutes les fenêtres sauf la fenêtre active |
| `Win + Ctrl + D` | Nouveau bureau virtuel |
| `Win + Ctrl + ← / →` | Changer de bureau virtuel |
| `Win + Ctrl + F4` | Fermer le bureau virtuel actif |
| `Win + 1…9` | Lancer / basculer vers l'application épinglée n° X de la barre des tâches |
| `Win + T` | Parcourir les icônes de la barre des tâches |
| `Win + B` | Zone de notification |

### Capture, saisie, affichage

| Raccourci | Action |
|-----------|--------|
| `Win + Shift + S` | Outil de capture d'écran (zone) |
| `Win + Impr écran` | Capture plein écran enregistrée dans Images > Captures d'écran |
| `Win + V` | Historique du presse-papiers |
| `Win + .` ou `Win + ;` | Panneau emojis |
| `Win + H` | Saisie vocale |
| `Win + Espace` | Changer la langue / disposition du clavier |
| `Win + P` | Mode d'affichage (dupliquer, étendre…) |
| `Win + K` | Se connecter à un écran sans fil (Diffuser) |
| `Win + G` | Xbox Game Bar |
| `Win + Alt + R` | Enregistrer l'écran (Game Bar) |
| `Win + +` / `Win + -` | Loupe : zoom avant / arrière |
| `Win + U` | Paramètres d'accessibilité |
| `Win + Ctrl + Entrée` | Narrateur |
| `Win + Ctrl + Shift + B` | Réinitialiser le pilote graphique (écran noir/figé) |

---

## 2. Autres raccourcis clavier

| Raccourci | Action |
|-----------|--------|
| `Ctrl + Shift + Échap` | Gestionnaire des tâches |
| `Ctrl + Alt + Suppr` | Écran de sécurité (verrouiller, changer d'utilisateur, tâches) |
| `Alt + Tab` | Changer de fenêtre |
| `Alt + F4` | Fermer la fenêtre (ou menu Arrêter sur le Bureau) |
| `Ctrl + C / X / V` | Copier / Couper / Coller |
| `Ctrl + Z / Y` | Annuler / Rétablir |
| `Ctrl + A` | Tout sélectionner |
| `Ctrl + Shift + N` | Nouveau dossier (Explorateur) |
| `F2` | Renommer |
| `F5` | Actualiser |
| `Shift + Suppr` | Supprimer définitivement (sans corbeille) |
| `Alt + Entrée` | Propriétés de l'élément sélectionné |
| `Shift` x5 | Touches rémanentes (accessibilité) |

---

## 3. Panneau de configuration : .cpl

*.cpl = Control Panel Library.*

| Commande | Ouvre |
|----------|-------|
| `ncpa.cpl` | Connexions réseau (cartes Ethernet, Wi-Fi) |
| `firewall.cpl` | Pare-feu Windows Defender |
| `appwiz.cpl` | Programmes et fonctionnalités (désinstaller) |
| `sysdm.cpl` | Propriétés système (nom du PC, variables d'environnement, restauration) |
| `main.cpl` | Propriétés de la souris |
| `desk.cpl` | Affichage (redirigé vers Paramètres sur Windows 10/11) |
| `inetcpl.cpl` | Options Internet |
| `intl.cpl` | Région et langue |
| `timedate.cpl` | Date et heure |
| `mmsys.cpl` | Son (lecture, enregistrement) |
| `powercfg.cpl` | Options d'alimentation |
| `hdwwiz.cpl` | Assistant Ajout de matériel |
| `bthprops.cpl` | Bluetooth |
| `joy.cpl` | Contrôleurs de jeu |
| `telephon.cpl` | Options de téléphonie et modem |
| `access.cpl` | Options d'ergonomie (ancienne interface) |

---

## 4. Consoles de gestion : .msc

*.msc = Microsoft Management Console (snap-in).*

### Postes de travail

| Commande | Ouvre |
|----------|-------|
| `compmgmt.msc` | Gestion de l'ordinateur (regroupe plusieurs outils) |
| `devmgmt.msc` | Gestionnaire de périphériques |
| `diskmgmt.msc` | Gestion des disques |
| `services.msc` | Services |
| `eventvwr.msc` | Observateur d'événements (logs) |
| `taskschd.msc` | Planificateur de tâches |
| `perfmon.msc` | Moniteur de performances |
| `lusrmgr.msc` | Utilisateurs et groupes locaux (*Pro+*) |
| `gpedit.msc` | Éditeur de stratégie de groupe locale (*Pro+*) |
| `secpol.msc` | Stratégie de sécurité locale (*Pro+*) |
| `wf.msc` | Pare-feu Windows avec fonctions avancées de sécurité |
| `fsmgmt.msc` | Dossiers partagés |
| `certmgr.msc` | Certificats de l'utilisateur actuel |
| `certlm.msc` | Certificats de l'ordinateur local |
| `tpm.msc` | Gestion du TPM |
| `rsop.msc` | Jeu de stratégies résultant |
| `wmimgmt.msc` | Contrôle WMI |
| `comexp.msc` | Services de composants |
| `printmanagement.msc` | Gestion de l'impression |

### Windows Server (outils d'administration, utiles en TSSR)

| Commande | Ouvre |
|----------|-------|
| `dsa.msc` | Utilisateurs et ordinateurs Active Directory |
| `dnsmgmt.msc` | Gestionnaire DNS |
| `dhcpmgmt.msc` | Gestionnaire DHCP |
| `gpmc.msc` | Gestion des stratégies de groupe (GPO) |
| `dssite.msc` | Sites et services Active Directory |
| `domain.msc` | Domaines et approbations Active Directory |

---

## 5. Outils et commandes (autres)

| Commande | Ouvre |
|----------|-------|
| `cmd` | Invite de commandes |
| `powershell` | PowerShell |
| `wt` | Terminal Windows |
| `taskmgr` | Gestionnaire des tâches |
| `regedit` | Éditeur du Registre |
| `msconfig` | Configuration du système (démarrage, services) |
| `msinfo32` | Informations système |
| `winver` | Version de Windows |
| `dxdiag` | Diagnostic DirectX |
| `resmon` | Moniteur de ressources |
| `mstsc` | Bureau à distance (RDP) |
| `control` | Panneau de configuration |
| `control userpasswords2` ou `netplwiz` | Comptes utilisateurs |
| `cleanmgr` | Nettoyage de disque |
| `dfrgui` | Optimiser les lecteurs (défragmentation) |
| `optionalfeatures` | Activer / désactiver des fonctionnalités Windows |
| `systempropertiesadvanced` | Propriétés système avancées |
| `mrt` | Outil de suppression de logiciels malveillants |
| `odbcad32` | Sources de données ODBC |
| `explorer` | Explorateur de fichiers |
| `notepad` / `calc` / `mspaint` | Bloc-notes / Calculatrice / Paint |
| `snippingtool` | Outil Capture d'écran |
| `magnify` / `osk` | Loupe / Clavier visuel |
| `charmap` | Table des caractères |

---

## 6. Commandes réseau et système (CMD)

| Commande | Rôle |
|----------|------|
| `ipconfig /all` | Configuration IP complète |
| `ipconfig /release` puis `/renew` | Libérer / renouveler le bail DHCP |
| `ipconfig /flushdns` | Vider le cache DNS |
| `ping <hôte>` | Tester la connectivité |
| `tracert <hôte>` | Tracer la route |
| `nslookup <nom>` | Interroger le DNS |
| `netstat -ano` | Connexions et ports ouverts (avec PID) |
| `getmac` | Adresse MAC |
| `arp -a` | Table ARP |
| `netsh` | Configuration réseau avancée |
| `hostname` | Nom de la machine |
| `whoami` | Utilisateur courant |
| `systeminfo` | Infos détaillées du système |
| `tasklist` / `taskkill /PID <n> /F` | Lister / tuer un processus |
| `sfc /scannow` | Vérifier et réparer les fichiers système |
| `DISM /Online /Cleanup-Image /RestoreHealth` | Réparer l'image Windows |
| `chkdsk /f` | Vérifier et réparer un disque |
| `gpupdate /force` | Forcer l'application des GPO |
| `net user` | Gérer les comptes locaux |
| `shutdown /s /t 0` | Arrêter immédiatement (`/r` = redémarrer) |

---

## 7. Dossiers spéciaux et URI

| Commande | Ouvre |
|----------|-------|
| `%appdata%` | Données d'application de l'utilisateur (Roaming) |
| `%localappdata%` | Données d'application locales |
| `%temp%` | Fichiers temporaires |
| `shell:startup` | Dossier de démarrage de l'utilisateur |
| `shell:common startup` | Dossier de démarrage de tous les utilisateurs |
| `shell:appsfolder` | Liste de toutes les applications |
| `ms-settings:` | Page d'accueil des Paramètres |
| `ms-settings:network` | Paramètres réseau |
| `ms-settings:windowsupdate` | Windows Update |
| `ms-settings:apps-volume` | Volume des applications 
