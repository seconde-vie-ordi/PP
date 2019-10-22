## Mise en garde
Faire attention le système pour les applications Android peut ralentir le système pour les ordinateurs qui sont déjà lent. Certaines applications ne marchent pas.

## Installer le gestionnaire d'application
1. Ouvrer l'application _Konsole_.
2. Copier cette commande et coller dans l'application (ctrl-shift-v) _Konsole_ et appuyer sur la touche ENTER. Attendre jusqu'à ce que la commande termine (Ça va prendre quelques minutes).


``` bash
sudo add-apt-repository ppa:morphis/anbox-support -y && sudo apt update && sudo apt install linux-headers-generic anbox-modules-dkms -y && sudo modprobe ashmem_linux && sudo modprobe binder_linux && sudo snap install --devmode --beta anbox && sudo apt install wget lzip unzip squashfs-tools dnsmasq -y && wget https://raw.githubusercontent.com/geeks-r-us/anbox-playstore-installer/master/install-playstore.sh && chmod +x install-playstore.sh && sudo ./install-playstore.sh && sudo ./install-playstore.sh --clean && rm install-playstore.sh
```

!> Pour régler les bugs graphiques lors du déplacement des fenêtres, il suffit d'ouvrir l'application _Configuration du système_ d'aller dans la section tout en bas **Matériel** > **Affichage et écran** > **Compositeur** et de décocher l'option _Permettre aux applications de bloquer la composition_.


3. Maintenant, vous pouvez accéder aux applications Android grâce à l'application _Anbox Aplication Manager_.

## Accéder au Google Play
1. Démarrer l'application _Anbox Aplication Manager_ pour ensuite ouvrir les paramètres Android.
2. Activer toute les permissions pour le _Google Play Store_ **Applications** > **Google Play Store** > **Permissions** et même chose pour les _Services Google Play_.
3. Maintenant vous pouvez vous connectez au Google Play Store
