
# 🇫🇷 Un Projet 100% Français, et j'en suis extrêmement fier !

Terminal-Vi est un projet conçu et développé en France, avec passion et enthousiasme. Il s'agit d'un interpréteur de commandes avancé qui apporte l’expérience Linux sur Windows, avec des commandes modifiées et optimisées.

L’objectif de Terminal-Vi est de rendre l’utilisation des commandes plus rapide, sans recherches complexes, tout en étant accessible aux nouveaux utilisateurs et puissant pour les plus expérimentés. Je suis extrêmement fier de ce travail et ravi de le partager avec la communauté.

Et surtout, vive la France, glorieuse, éternelle et invincible, rien ne peut l’arrêter !

# 🔒 Actuellement Privé, Bientôt Open Source
Terminal-Vi est pour l’instant un projet privé, mais une fois qu’il aura une communauté assez grande, il passera en open source pour que chacun puisse contribuer et l’améliorer.

# Il permet de faire quoi ?
⚡ Terminal-Vi : Un Terminal Sans Limites !
Terminal-Vi est bien plus qu'un simple interpréteur de commandes. Il intègre apt, prend en charge des milliers de modules et repose sur des fournisseurs de packages externes pour offrir une puissance inégalée. Grâce à son système avancé de gestion de paquets (Bios v2), il permet d’accéder à tout type de fichiers, logiciels, extensions et contenus, sans aucune exception.

Que ce soit pour installer des programmes, télécharger des fichiers, contourner des restrictions ou explorer des bases de données externes, Terminal-Vi offre un accès total et illimité à un écosystème gigantesque. 🚀


# Gestionnaire de Paquets.
Par défaut, Terminal-Vi utilise [APT-Catalog](https://github.com/virusinfo2/APT_Catalog) comme catalogue principal pour la gestion de paquets. Cela permet d’accéder à une vaste collection de logiciels, extensions et outils, tout en facilitant l'installation et la mise à jour des paquets directement depuis le terminal.


# 1 - 💻 Installation et traduction 🌍

### 💾 Installer avec Git.

```bash
  git clone https://github.com/virusinfo2/Terminal-VI_py.git
  cd Terminal-VI_py
  pip install -r requirement-Win.txt
  python Main.py
```

### 🌍 Installer le Module de traduction automatique.
#### 👨‍💻 Depuis le Terminal .

```sh
  apt update --all
  apt install AutoTranslation -y
```

#### 💾 Depuis Git .

```sh
  cd /Module/
  git clone https://github.com/virusinfo2/AutoTranslation.git
```


# ⌨️ 2 - Commande

### Helper
#### Voir les commandes disponible :
```sh
help
```


### Voicie les commandes de base :

####  Module :
Mettre à jour les fichiers d’index des dépôts.
```sh
apt update
```

Installer un paquet.
```sh
apt install <module>
```

Supprimer un paquet.
```sh
apt remove <module>
```

Mettre a jour les paquets.
```sh
apt upgrade
```

Mettre a jour le paquet.
```sh
apt upgrade <module>
```

Test complet sur l'entièreté des paquet (Trouver la moindre erreur).
```sh
check integrity
```

Proposse tous les paquets installable, le tous en une interface "GUI".
```sh
apt install --GUI
```

####  Autre :

Afficher l'historique des commandes.
```sh
history
```

Permet d'injecter du code python directement dans le programme.
```sh
inject:<code>
```

Purger le système (Vide temp et le Cache). ⚠️ ( Non disponible ) ⚠️
```sh
purge
```

Mets a jour le Software. ⚠️ ( Non disponible ) ⚠️
```sh
sys:update
```

Afficher les information du Software. ⚠️ ( Non disponible ) ⚠️
```sh
sys:version
```



# 👨‍💻 3 - Développeur

## 💾 3.1 - Cache

#### 🔍 inspection :

```python 
inject:with Cache.lock: Cache.inspect()
```

#### 🧹 suppression :

```python 
inject:with Cache.lock: Cache.cache = {}
```
# ❓ 4 - FAQ

### ⚙️ 1 - OS.

#### 1.0 - Terminal-Vi est-il compatible avec tous les systèmes d'exploitation ?

Terminal-Vi est actuellement conçu pour Windows (développé principalement sur Windows 10 x64). Il est prévu de créer une version compatible avec Linux dans un futur.


### 🤝 2 - Open Source.
#### 2.0 - Terminal-Vi est-il open source ?

Pour l’instant, Terminal-Vi est privé. Il deviendra open source lorsque la communauté sera assez grande pour assurer son développement collaboratif.

#### 2.1 - Quand Terminal-Vi sera-t-il disponible en open source ?
Terminal-Vi deviendra open source dès que nous aurons une base solide d’utilisateurs et de contributeurs. Nous souhaitons d’abord assurer une version stable et robuste avant de permettre à la communauté de participer pleinement au développement.

### 🛠️ 3 - amélioration.
#### 3.0 - Puis-je suggérer des améliorations ou signaler des bugs ?

Oui ! Une plateforme de feedback sera mise en place pour permettre aux utilisateurs de proposer des idées et d’aider à l’amélioration du projet.

### 🛡️ 4 - sécurité.

#### 4.0 - Est-ce que Terminal-Vi remplace l'invite de commandes ou PowerShell ?

Non, Terminal-Vi ne remplace pas l'invite de commandes ou PowerShell. Il s'agit plutôt d'un complément qui permet d'exécuter des commandes Linux adaptées à Windows pour une utilisation plus rapide et simplifiée, tout en restant compatible avec les outils natifs de Windows.

#### 4.1 - Terminal-Vi est-il sécurisé à utiliser ?
Oui, Terminal-Vi est conçu avec la sécurité en tête. Cependant, comme pour tout programme qui interagit avec votre système, il est important de toujours vérifier les sources et de faire preuve de prudence lors de l’utilisation de commandes puissantes. Il est fortement recommandé de ne pas ajouter de sources inconnues dans le gestionnaire de paquets, afin d'éviter d'exécuter des commandes ou d'installer des logiciels potentiellement malveillants.

### 🌐 5 - Support Multilingue.

#### 🌍 5.0 - Support Multilingue à Venir ?
Les traductions dans d’autres langues seront ajoutées plus tard, soit par traduction automatique, soit par la contribution de bénévoles. Restez à l’affût des mises à jour !

#### 🗣️ 5.1 - Langues Prévues

🤖 = Traduction automatique.

🤝 = Traduit par la communauté.

|   Langue   | Prévu | Présent  | Mode de traduction |
|:----------:|:-----:|:--------:|:-------------------:
|  Anglais   |  ✅  |    ❌    |         🤝         |
|  Allemand  |  ✅  |    ❌    |         🤝         |
|  Espagnol  |  ✅  |    ❌    |         🤝         |
|  Italien   |  ❌  |    ❌    |
|  Russe     |  ✅  |    ❌    |         🤖         |
|  Français  |  ✅  |    ✅    |         🤝         |
|  Chinois   |  ❌  |    ❌    |
|  Arabe     |  ❌  |    ❌    |
|  Portugais |  ✅  |    ❌    |         🤖         |
|  Hébreu    |  ❌  |    ❌    |

D'autres langues pourront être ajoutées en fonction des contributions et des demandes de la communauté ! 🌍✨
## Auteurs

- [@VirusInfo](https://www.tiktok.com/@virus_info)

## Download Releases
| Version     |      Build     |PyVersion|BiosVersion|   Date   | Lien |
|:-----------:|:--------------:|:-------:|:---------:|:--------:|:----:|
| 0.00.01     |08.03.2025.18.00| 3.11.9  | 0.2       |08.03.2025|  ❌ |
| 0.00.01     |03.12.2024.21.12| 3.11.9  | 0.1       |03.12.2024|  ❌ |