# The Infinite Tower — README

> Projet MMO‑RPG. Ce document sert à la fois de guide **joueur** (installation, lancement via `launcher.bat`) et de mémo **équipe** (structure des fichiers, mises à jour, règles de progression et d’économie).

## TL;DR (Jouer en 30 secondes)

1. **Télécharge** la dernière release *(archive ZIP)* depuis la page officielle.
2. **Dézippe** où tu veux (évite `Program Files`).
3. **Double‑clique** sur `launcher.bat`.

   * Le launcher **met à jour** les fichiers si besoin, puis **lance** le jeu.
4. **Crée un compte** en jeu → **Connecte‑toi** → **Joue**.

> Si Windows bloque l’exécution (SmartScreen) : *Informations complémentaires* → *Exécuter quand même*.
> Si PowerShell bloque le script : le `launcher.bat` force un mode « Bypass » pour l’exécution (aucune install système nécessaire).

## Concept & Objectif du jeu

* **Univers** : une tour sans fin, des étages procéduraux et des paliers de difficulté.
* **Boucle de gameplay** :

  1. **Explorer / combattre** pour récupérer des ressources,
  2. **Crafter / améliorer** ton équipement,
  3. **Monter d’étages** et affronter des **boss de palier**,
  4. **Revenir au camp** pour convertir les trouvailles en puissance,
  5. Recommencer, mais **plus haut**.
* **Progression** : l’équipement passe par des **Tiers** : `T0 → T1 → T2 → T3 → T3‑EX`.

> Le jeu **n’exige pas de cash‑shop**. Toute la puissance se gagne **en jouant**.

## Contrôles (par défaut Intersect)

* Déplacement : WASD (ou flèches)
* Interagir / Parler : **E**
* Attaque / Sorts : barres de raccourcis
* Inventaire : **I**
* Personnage / Equipement : **C**
  *(Tous remappables dans **Options**.)*

## Dépannage (FAQ rapide)

**SmartScreen / Antivirus bloque**
→ Autorise manuellement. Le client et le launcher ne modifient pas le système.

**PowerShell refuse d’exécuter l’updater**
→ Le launcher passe en `-ExecutionPolicy Bypass`. Si ça bloque encore : clic droit → *Exécuter en tant qu’administrateur* (une fois), puis relance normale.

**Erreur réseau / impossible de se connecter**
→ Serveur en maintenance ou **version décalée**. Lancer `launcher.bat` pour forcer la **mise à jour**. Vérifier ton **pare‑feu**. OU veuillez télécharger la version **V.0.1.0** dans les release du Github.

## Support & signalement de bugs

* **Bugs** : joindre un **log client** (`/logs`) + contexte (où, quoi, comment reproduire).
* **Gameplay** : indiquer l’**étage**, l’**équipement**, la **recette** concernée.
* **Contact** : `#bugs-report` sur Discord.
