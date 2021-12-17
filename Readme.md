# Serveur GFL FR

- [Serveur GFL FR](#serveur-gfl-fr)
  - [Règles](#règles)
  - [Mod](#mod)
    - [Installation](#installation)
      - [Forge](#forge)
      - [Modpack](#modpack)

## Règles

Le serveur est à la version <u>1.12.2</u>.<br />
<br />
**10 joueurs maximum en même temps**. Cette règle a été mise en place pour éviter la saturation de la ram.<br />
<br />
*Antinomi* est le propriétaire du serveur, mais s'il est absent, *AFKoide* a les droits d'admin (si il abuse, hésitez pas à le reporter).<br />
Si vous avez des mods a rajouter, proposer les dans #autres-jeux. Le lien vers le modpack s'y trouvera également.<br />
<br />
<br />
Chaque joueur a le droit à un échelon de 5 dolls maximum : les dolls supplémentaires pourront être conservé sous forme d'armes et de cores d'arme.<br />
<br />
Le PVP est actif et non sanctionné, mais c'est à vos risques et périls.<br /> 
<br /> 

## Mod

La liste des mods se trouve [ici](https://afkoide.github.io/GFL_FR/).

### Installation

#### Forge

Tout d'abord, il faut installer [forge 1.12.2](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html) (mise a jour supérieur à 14.23.5.2856).<br/>
Une fois le fichier .jar télécharger, il faut l'executer ; un message d'avertissement devrait apparaître (vous pouvez l'ignorer).<br />
Une fenêtre d'installation devrait s'ouvrir : si Minecraft est déjà installé sur votre ordinateur, l'installateur trouvera automatiquement le dossier (le chemin devrait ressembler à: *C:\Users\[nom de la session]\AppData\Roaming\.minecraft*). <br />
<br />
Une fois l'installation terminée, ouvrez le launcher Minecraft. Dans l'onglet **Configuration**, faites une **Nouvelle Configuration**.
- Choisissez le nom que vous souhaitez.
- Choisissez la version Forge dans le menu déroulant.
- Créez un répertoire du jeu : Parcourir > Créer un nouveau dossier > [Nommer le dossier].
- Dans **Plus d'Options**, remplacez le 2 qui se trouve dans **Arguments JVM** par un 6/8 ; il s'agit de la ram que vous allouez au jeu : il sera impossible charger certains mod si vous avez moins de 6Gb.
<br />
Une fois ces opérations faites, **Créer** et appuyer sur **Jouer**. Forge & Minecraft vont prendre un certain temps pour créer et configurer les dossiers nécessaires.

Une fois sur le menu de base de Minecraft, vous pouvez quitter le jeu et passer à l'étape suivante.

Pour un guide d'installation plus détaillé, consulter [ce guide](https://minecraftfacile.com/installer-minecraft-forge/).<br />

#### Modpack

Ce modpack doit être décompresser dans le dossier mods de votre Minecraft. Ce dernier se trouve dans Appdata > Roaming > .minecraft (> [Nom du Profil]).<br />
<br />
Ce modpack est composé d'un dossier *mods* qui contient tous les mods utilisé, et d'un second dossier *client* : <br />
- Pour la partie <u>serveur</u>, le dossier client est inutile (ce sont des mods locaux).
- Pour le launcher <u>client</u>, ajouter les mods du dossier client dans le dossier parent (mods).