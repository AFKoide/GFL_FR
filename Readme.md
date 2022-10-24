# Serveur GFL FR

- [Serveur GFL FR](#serveur-gfl-fr)
  - [Règles](#règles)
  - [Mod](#mod)
    - [Installation](#installation)
      - [Forge](#forge)
      - [Modpack](#modpack)

## Règles

Le serveur est à la version <u>1.12.2</u> et necessite une version officielle de Minecraft.<br />
<br />
**10 joueurs maximum en même temps**. Cette règle a été mise en place pour éviter la saturation de la ram.<br />
<br />
*Antinomi* est le propriétaire du serveur, mais s'il est absent, *AFKoide* a les droits d'admin (si il abuse, hésitez pas à le reporter).<br />
Si vous avez des mods a rajouter, proposer les dans #autres-jeux. N'hésitez pas à ping *AFKoide* pour le lien du modpack.<br />
<br />
<br />
Chaque joueur a le droit à un échelon de 5 dolls maximum : les dolls supplémentaires pourront être conservé sous forme d'armes et de cores d'arme. Cette règle a été établie pour la même raison que la limite de joueur : la RAM est limitée.<br />
<br />
Le PVP est actif et non sanctionné.<br /> 

[Lien de la version actuelle](https://github.com/AFKoide/GFL_FR/releases/download/modpack/mods.rar)
[Lien de la prochaine version](https://github.com/AFKoide/GFL_FR/releases/download/future/mods.rar)

## Mod

La liste des mods se trouve [ici](https://github.com/AFKoide/GFL_FR/blob/main/Liste%20des%20Mods.md).

### Installation

#### Forge

Tout d'abord, il faut installer [forge 1.12.2](https://files.minecraftforge.net/net/minecraftforge/forge/index_1.12.2.html) (mise a jour supérieur à 14.23.5.2856) pour que le mod GFL fonctionne.<br/>
Une fois téléchargé, executer le fichier ; un message d'avertissement devrait apparaître : ignorer le.<br />
Une fenêtre d'installation devrait s'ouvrir : si Minecraft est déjà installé sur votre ordinateur, l'installateur trouvera automatiquement le répertoire de Minecraft (le chemin devrait ressembler à: *C:\Users\[nom de la session]\AppData\Roaming\.minecraft*). <br />
<br />
L'installation finie, ouvrez le launcher officiel de Minecraft (si c'est ce que vous utilisez) et allez dans l'onglet **Configuration**. Cliquez sur **Nouvelle Configuration** : nous allons créer une session pour le modpack.
- Choisissez un nom pour votre session (par exemple, GFL).
- Choisissez la version Forge que vous venez d'installer dans le menu déroulant (le nom contient Forge, 1.12.2 et la version de Forge installée).
- Pour plus de facilité dans la gestion des fichiers, créez un répertoire du jeu : toujours dans le launcher, cliquez sur Parcourir > Créer un nouveau dossier et [tapez le même nom que votre session].
- Dans **Plus d'Options**, remplacez le 2 qui se trouve dans **Arguments JVM** par un 6 ou un 8. Cet argument défini la mémoire vive allouée à Minecraft ; il est impossible de lancer ce modpack avec moins de 6Mb de RAM. <br>
`-Xmx2G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M` deviendra <br>
`-Xmx6G -XX:+UnlockExperimentalVMOptions -XX:+UseG1GC -XX:G1NewSizePercent=20 -XX:G1ReservePercent=20 -XX:MaxGCPauseMillis=50 -XX:G1HeapRegionSize=32M`

<br />
Une fois ces opérations faites, **Créer** et appuyer sur **Jouer**. Minecraft va prendre un certain temps pour créer et configurer les dossiers nécessaires pour Forge.

Une fois sur le menu de base de Minecraft, vous pouvez quitter le jeu et passer à l'étape suivante.

Pour un guide d'installation plus détaillé, consulter [ce guide](https://minecraftfacile.com/installer-minecraft-forge/).<br />

#### Modpack

Ce modpack doit être décompresser dans le répertorie de votre session, dans le dossier Minecraft. Ce dernier se trouve dans Appdata > Roaming > .minecraft > [Nom choisit plus tôt].<br />

