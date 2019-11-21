## Comment installer des applications Windows?
Dans ce tutoriel, je vais vous montrer comment pouvoir installer des applications Windows(.exe) si l'application que vous avez besoin n'est pas disponible sous Linux.

## Mise en garde
Ce ne sont pas toutes les applications Windows qui marchent pour savoir si l'application que vous voulez installer marche, vous pouvez consulter ce [site](https://appdb.winehq.org/index.php).

## Installer des applications Windows avec Wine
1. Ouvrer l'application _Konsole_.
2. Copier cette commande et coller dans l'application (ctrl-shift-v) _Konsole_ et appuyer sur la touche ENTER. Attendre jusqu'à ce que la commande termine (Ça va prendre quelques minutes).


``` bash
sudo dpkg --add-architecture i386 && wget -nc https://dl.winehq.org/wine-builds/winehq.key && sudo apt-key add winehq.key && sudo apt-add-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ bionic main' -y && sudo apt update && sudo apt install --install-recommends winehq-devel -y
```

3. Vous n'avez qu'à exécuter le fichier _.exe_ de l'application que vous voulez installer.
