## Pourquoi des applications alternatives?
Certaines applications ne sont tout simplement pas disponible sous Linux, mais il existe de nombreuses alternatives libres et gratuites qui peuvent les remplacer et qui sont en général plus légère pour les vieux ordinateurs. Sachez qu'en général tout application ayant une version Web peut être utilisé va être compatible (ex:Google Docs).

## Les alternatives
Voici une série d'alternatives par catégorie pour installer l'alternative vous n'avez qu'à exécuter la ligne de commande associée.

<!-- tabs:start -->

#### ** Bureautique **
Pour lire des pdf, mais aussi toutes sortes de format.
- Okular (Installé par défaut)


Pour remplacer Office (Word, PowerPoint et Excel):

- [Libreoffice](https://fr.libreoffice.org/) (Writer, Impress et Calc)


```bash
sudo add-apt-repository ppa:libreoffice/ppa -y && sudo pkcon refresh && sudo apt install libreoffice-kde5 libreoffice-writer libreoffice-impress libreoffice-calc mythes-fr libreoffice-l10n-fr libreoffice-help-fr
```

#### ** Graphisme **
Pour remplacer Photoshop:
- [Krita](https://krita.org/fr/)

```bash
sudo apt install krita
```
- [Gimp](https://www.gimp.org/fr/)

```bash
sudo add-apt-repository ppa:otto-kesselgulasch/gimp -y && sudo pkcon refresh && sudo apt install gimp
```
#### ** Multimédia **
Comme logiciel de montage vidéo:
- [Kdenlive](https://kdenlive.org/fr/)

```bash
sudo apt install kdenlive
```

<!-- tabs:end -->
