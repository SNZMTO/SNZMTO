# Mateo Sanchez

Étudiant à **42 Marseille**, je cherche une **alternance de développeur, full-stack ou IA, dès avril 2027, pour deux ans**
(deux semaines en entreprise, une à l'école), à Aix-Marseille. En alternance, je préparerai le titre RNCP 6 « Concepteur
développeur de solutions informatiques » (RNCP 39783, **niveau Bac+3**). Je construis des outils qui branchent Claude sur
de vrais logiciels, et je les mets en ligne.

<p>
  <a href="https://mateosan.fr"><img src="https://img.shields.io/badge/Portfolio%20et%20CV-mateosan.fr-E2A72E?style=flat-square&labelColor=2A1E17" alt="Portfolio et CV : mateosan.fr"></a>
  <a href="mailto:sanchezmateo@proton.me"><img src="https://img.shields.io/badge/E--mail-sanchezmateo%40proton.me-E2A72E?style=flat-square&logo=protonmail&logoColor=white&labelColor=2A1E17" alt="E-mail"></a>
  <a href="https://www.linkedin.com/in/mat%C3%A9o-sanchez-2607883a0"><img src="https://img.shields.io/badge/LinkedIn-Mateo%20Sanchez-1E6E78?style=flat-square&logo=linkedin&logoColor=white&labelColor=2A1E17" alt="LinkedIn"></a>
</p>

> **In English.** Student at 42 Marseille, looking for a two-year apprenticeship as a full-stack or AI developer from
> April 2027 (two weeks at work, one at school), around Aix-Marseille. I build tools that plug Claude into real software,
> and I ship them. Portfolio and CV: [mateosan.fr](https://mateosan.fr).

## Ce que je sais faire, et où le voir

| Ce que je fais | Où le voir |
| --- | --- |
| Un serveur MCP en production : SDK officiel, Streamable HTTP, MCP Apps | [honear-mcp](https://github.com/SNZMTO/honear-mcp), en ligne sur [mcp.honear.fr](https://mcp.honear.fr) : [`serveurs/public.py`](https://github.com/SNZMTO/honear-mcp/blob/main/src/honear_mcp/serveurs/public.py) |
| Du TypeScript strict et du temps réel | [honear](https://github.com/SNZMTO/honear) : [`src/reseau/ligne.ts`](https://github.com/SNZMTO/honear/blob/main/src/reseau/ligne.ts), le WebSocket et ses limites |
| Des tests qui tiennent l'architecture | [`tests/sources.test.ts`](https://github.com/SNZMTO/honear/blob/main/tests/sources.test.ts) et [`tests/test_sources.py`](https://github.com/SNZMTO/honear-mcp/blob/main/tests/test_sources.py) : un test rouge, c'est une règle enfreinte |
| Une mise en production durcie | [`deploiement/compose.yaml`](https://github.com/SNZMTO/honear/blob/main/deploiement/compose.yaml) : lecture seule, aucune capacité Linux, aucun port publié ; la CI à chaque envoi |
| Un serveur Linux tenu pas à pas | [homelab](https://github.com/SNZMTO/homelab) : SSH par clé, pare-feu, [fail2ban vérifié jusque dans le noyau](https://github.com/SNZMTO/homelab/blob/main/docs/phase1-fail2ban.md) |
| Travailler avec Claude Code | [DIciELa](https://github.com/SNZMTO/DIciELa) : [`CLAUDE.md`](https://github.com/SNZMTO/DIciELa/blob/main/CLAUDE.md), ses procédures et [un garde-fou testé](https://github.com/SNZMTO/DIciELa/blob/main/Tools/garde-unity.test.js) |

## Deux projets

<table>
  <tr>
    <td width="50%" valign="top">
      <a href="https://github.com/SNZMTO/honear-mcp"><img src="images/honear-mcp.webp" alt="Le MCP de Honear dans claude.ai : le mini blind test s'ouvre dans la conversation"></a>
      <h3><a href="https://github.com/SNZMTO/honear-mcp">honear-mcp</a></h3>
      Le connecteur de Honear pour Claude : on demande une playlist de blind test, le serveur retrouve chaque titre chez
      Deezer, écarte ce qui se joue mal et rend le lien de la partie, ou la fait jouer dans la conversation. Python, SDK
      MCP officiel, Pydantic, Docker, plus de 450 tests.
    </td>
    <td width="50%" valign="top">
      <a href="https://github.com/SNZMTO/honear"><img src="images/honear.svg" alt="Honear : la platine de l'accueil sur le meuble en noyer"></a>
      <h3><a href="https://github.com/SNZMTO/honear">honear</a></h3>
      Le blind test multijoueur qui joue ces listes, en ligne sur <a href="https://honear.fr">honear.fr</a> : un écran pour
      la tablée, un téléphone chacun. TypeScript strict, WebSocket, plus de 500 tests, Docker durci, registre RGPD.
    </td>
  </tr>
</table>

Et aussi : [DIciELa](https://github.com/SNZMTO/DIciELa), un jeu de gestion en prototype sous Unity, dont Claude Code écrit
le C# dans un cadre que j'ai posé ; [homelab](https://github.com/SNZMTO/homelab), le journal du VPS qui héberge tout ça ;
[mateosan.fr](https://github.com/SNZMTO/mateosan.fr), ma vitrine, lisible sans JavaScript.

## Comment je travaille avec Claude

- **Claude Code écrit l'essentiel du code et des tests.** Les commits sont co-signés, et chaque dépôt le dit.
- **Je conçois et je tranche** : le produit, l'architecture, et les règles que les tests vérifient.
- **J'essaie sur de vrais appareils** : sur Honear, plusieurs bugs ne se voyaient que sur iPhone.
- **Le cadre est dans le dépôt** : ce qui tient l'assistant d'une session à l'autre (règles, procédures, garde-fou,
  décisions numérotées) se lit dans le `CLAUDE.md` et le dossier `.claude/` de chaque projet.

## À 42

Depuis novembre 2025, tout à la main, sans assistant : du C, du Python et du système. Chaque projet est corrigé par d'autres
étudiants, qui me font expliquer mon code. Ce code reste privé ; je le montre volontiers en entretien. Je suis aussi
ambassadeur de 42 Marseille, sur les salons et aux présentations de l'école.

<details>
<summary><b>Le détail des projets</b> : 11 en Python, 4 en C, 3 en système et réseau</summary>

| Domaine | Projet | En bref |
| --- | --- | --- |
| **Python** | Growing Code, Garden Guardian | Les bases : fonctions, récursion, exceptions |
| | Code Cultivation, Code Nexus | L'objet : héritage, classes abstraites, un pipeline de données |
| | Data Quest, Data Archivist, Cosmic Data | Les données : collections, fichiers, validation avec Pydantic |
| | The Codex, The Matrix | Les paquets, les imports, les environnements virtuels |
| | A-Maze-ing, Pac-Man | Un labyrinthe généré, puis un Pac-Man jouable dessus, en binôme |
| **C** | libft, ft_printf | Réécrire la libc de base et `printf` |
| | get_next_line, push_swap | Lire ligne par ligne ; trier une pile en un minimum de coups |
| **Système et réseau** | Born2beRoot | Un serveur en machine virtuelle : LVM chiffré, SSH sans root, pare-feu, `sudo` encadré |
| | Net_Practice | Adresses IP, masques, routeurs et passerelles, en dix niveaux |
| | Inception | NGINX en TLS, WordPress et MariaDB sous Docker Compose, Dockerfiles écrits à la main |

</details>

---

**Game jams** : *Masquarade* (Global Game Jam 2026) et [*Sueurs chaudes*](https://masalvad.itch.io/sueurs-chaudes)
(Jam Academy 2026, sélectionné par un jury de studios, dont CD Projekt : [la vidéo](https://www.youtube.com/watch?v=7yN_nlvvNGY)),
en équipes de quatre, sur GameMaker. **Hors code** : le voyage, la fantasy et la science-fiction.
