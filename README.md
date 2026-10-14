# Bienvenue, moi c'est Mateo 👋

Étudiant à **42 Marseille**, j'aime construire des outils qui tournent pour de vrai.
Je cherche une **alternance en développement**, côté data, IA ou full-stack.

<p>
  <a href="mailto:sanchezmateo@proton.me"><img src="https://img.shields.io/badge/E--mail-sanchezmateo%40proton.me-E2A72E?style=flat-square&logo=protonmail&logoColor=white&labelColor=2A1E17" alt="E-mail"></a>
  <a href="https://www.linkedin.com/in/mat%C3%A9o-sanchez-2607883a0"><img src="https://img.shields.io/badge/LinkedIn-Mat%C3%A9o%20Sanchez-1E6E78?style=flat-square&logo=linkedin&logoColor=white&labelColor=2A1E17" alt="LinkedIn"></a>
</p>

## 🎓 En deux mots

- **Ma formation** : le tronc commun du cursus 42 Next, que j'aurai fini pour mon entrée en alternance. Ensuite, en
  alternance, le titre RNCP 7 « Expert en architecture informatique », option **Architecture de bases de données et data**
  (niveau Bac+5).
- **Mon rythme** : deux semaines en entreprise, une semaine à l'école.
- **Ce que je cherche** : une équipe où je construis des outils qui servent vraiment, et avec qui j'aurais envie de continuer
  après l'alternance.

## 🛠️ Mes projets

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SNZMTO/honear"><img src="images/honear.svg" alt="Honear : la platine de l'accueil sur le meuble en noyer"></a>
      <h3><a href="https://github.com/SNZMTO/honear">Honear</a></h3>
      Un blind test multijoueur, en ligne sur <a href="https://honear.fr">honear.fr</a> : un écran pour la tablée, un
      téléphone chacun. TypeScript strict, WebSocket, 523 tests, Docker durci, registre RGPD.
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SNZMTO/DIciELa"><img src="images/diciela.webp" alt="DIciELa : la Chimère sur le panneau de bois du jeu"></a>
      <h3><a href="https://github.com/SNZMTO/DIciELa">DIciELa</a></h3>
      Un jeu de chaînes de production, fantasy et cozy, en prototype sous Unity. Une simulation en C# pur vérifiée par
      540 tests, et tout un cadre pour garder le projet cohérent : règles, procédures, garde-fou, décisions numérotées.
    </td>
  </tr>
</table>

## ⚙️ Comment je travaille

- **À 42, tout à la main.** Du C et du Python, sans assistant : libft, ft_printf, get_next_line, push_swap, puis les
  modules Python. Chaque projet est corrigé par d'autres étudiants, qui me font expliquer mon code.
- **Sur mes projets perso, avec un assistant de code.** Je conçois, je découpe le code en couches, j'écris les règles et les
  tests qui les verrouillent, et j'utilise Claude Code pour écrire plus vite. Je relis, j'essaie sur de vrais appareils, et
  je tranche. Chaque projet dit qui a fait quoi.
- **Un cadre qui se lit.** Sur DIciELa, ce qui tient l'assistant d'une session à l'autre est dans le dépôt :
  [`CLAUDE.md`](https://github.com/SNZMTO/DIciELa/blob/main/CLAUDE.md), les règles, les procédures et le hook garde-fou de
  [`.claude/`](https://github.com/SNZMTO/DIciELa/tree/main/.claude), et
  [les décisions numérotées](https://github.com/SNZMTO/DIciELa/blob/main/Docs/DECISIONS.md).

## 🏫 À 42

Le code de ces projets reste privé.

<details>
<summary><b>🐍 Python</b> · bases du langage, objet, données, paquets et environnement, algorithmique · 11 projets</summary>

| Domaine | Projet | En bref |
| --- | --- | --- |
| **Bases du langage** | Growing Code | Variables, fonctions, boucles et récursion |
| | Garden Guardian | Lever, attraper et définir ses propres exceptions |
| **Programmation objet** | Code Cultivation | Classes, héritage, encapsulation |
| | Code Nexus | Classes abstraites et polymorphisme, autour d'un pipeline de données |
| **Données** | Data Quest | Listes, dictionnaires, ensembles, générateurs |
| | Data Archivist | Lire et écrire des fichiers, gestionnaires de contexte |
| | Cosmic Data | Valider des données avec des modèles Pydantic et des énumérations |
| **Paquets et environnement** | The Codex | Organiser un projet en paquets, gérer les imports |
| | The Matrix | Environnements virtuels, variables d'environnement, dépendances |
| **Algorithmique et jeu** | A-Maze-ing | Générer un labyrinthe à partir d'un fichier de configuration |
| | Pac-Man | Un Pac-Man jouable sur les labyrinthes d'A-Maze-ing, avec Pygame, en binôme |

</details>

<details>
<summary><b>🧱 C</b> · bibliothèque standard, entrées et sorties, algorithmique · 4 projets</summary>

| Domaine | Projet | En bref |
| --- | --- | --- |
| **Bibliothèque standard** | libft | Réécrire les fonctions de base de la libc : chaînes, mémoire, listes chaînées |
| | ft_printf | Réimplémenter `printf` et ses conversions, avec des fonctions variadiques |
| **Entrées et sorties** | get_next_line | Lire un fichier ligne par ligne, avec un tampon et un état gardé entre les appels |
| **Algorithmique** | push_swap | Trier une pile avec un jeu d'opérations limité, en un minimum de coups |

</details>

<details>
<summary><b>🌐 Système et réseaux</b> · administration d'un serveur, réseau IP, conteneurs · 3 projets</summary>

| Domaine | Projet | En bref |
| --- | --- | --- |
| **Administration système** | Born2beRoot | Monter son premier serveur dans une machine virtuelle : partitions chiffrées sous LVM, SSH sans root sur un port dédié, pare-feu, politique de mots de passe stricte, `sudo` encadré |
| **Réseau** | Net_Practice | Configurer de petits réseaux simulés, en dix niveaux : adresses IP, masques de sous-réseau, routeurs et passerelles |
| **Conteneurs** | Inception | Une infrastructure Docker Compose dans une machine virtuelle : NGINX en TLS comme seule entrée, WordPress avec php-fpm, MariaDB, des Dockerfiles écrits à la main, des volumes nommés et un réseau dédié |

</details>

## 🎮 Game jams

| Jeu | Jam | En bref |
| --- | --- | --- |
| **Masquarade** | Global Game Jam 2026, thème « Masque » | Un bal masqué entre quatre duchés, où l'on joue un paysan caché sous un masque. En équipe de quatre, sur GameMaker. |
| **[Sueurs chaudes](https://masalvad.itch.io/sueurs-chaudes)** | Jam Academy 2026 | Un robot mécanicien rouillé dans une usine steampunk : surveiller la pression des vannes, chasser les araignées et garder la chaudière chaude. En équipe de quatre, sur GameMaker. |

## 🧰 Ce que j'utilise

<p>
  <img src="https://img.shields.io/badge/TypeScript-2A1E17?style=flat-square&logo=typescript&logoColor=E2A72E" alt="TypeScript">
  <img src="https://img.shields.io/badge/Node.js-2A1E17?style=flat-square&logo=nodedotjs&logoColor=E2A72E" alt="Node.js">
  <img src="https://img.shields.io/badge/Python-2A1E17?style=flat-square&logo=python&logoColor=E2A72E" alt="Python">
  <img src="https://img.shields.io/badge/C-2A1E17?style=flat-square&logo=c&logoColor=E2A72E" alt="C">
  <img src="https://img.shields.io/badge/C%23%20%2F%20Unity-2A1E17?style=flat-square&logo=unity&logoColor=E2A72E" alt="C# et Unity">
  <img src="https://img.shields.io/badge/PostgreSQL%20%2F%20Supabase-2A1E17?style=flat-square&logo=supabase&logoColor=E2A72E" alt="PostgreSQL et Supabase">
  <img src="https://img.shields.io/badge/Docker-2A1E17?style=flat-square&logo=docker&logoColor=E2A72E" alt="Docker">
  <img src="https://img.shields.io/badge/Linux-2A1E17?style=flat-square&logo=linux&logoColor=E2A72E" alt="Linux">
  <img src="https://img.shields.io/badge/Git-2A1E17?style=flat-square&logo=git&logoColor=E2A72E" alt="Git">
  <img src="https://img.shields.io/badge/Claude%20Code-2A1E17?style=flat-square&logo=claude&logoColor=E2A72E" alt="Claude Code">
</p>

## 🌍 Hors code

J'adore voyager, et je lis beaucoup de fantasy et de science-fiction. Mes trois sagas préférées : *Dungeon Crawler Carl*,
*Red Rising* et *Shadow Slave*.
