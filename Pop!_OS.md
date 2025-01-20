# Pop!\_OS

1. Désactiver le secure boot du BIOS avant installation.
2. Mettre à jour via `sudo apt update && upgrade` puis redémarrer
3. Installer PHP et Composer via la CLI de Laravel (ou apt)
4. Installer NodeJS
5. Installer MariaDB
6. Installer VSCode (via flatpack ou apt ou paquet .deb)
7. _DashToPanel_ et _Extensions_ normalement déjà installés

Enjoy it ;)

## Optionnel

1. Durant installation, possibilité ou non d'encrypter les DD
2. Configurer les préférences (localisation, keyboard, timezone, privacy, ...)
3. Créer un compte utilisateur local
4. Installer snap via `sudo apt install snapd`
5. Configurer snap via `snap install hello-world && hello-world`
6. Installer flatpack via `sudo apt install flatpak`
7. Configurer flatpack via `flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrep`
8. Installer GNOME soit :
   a. Via Flatpack `sudo apt install gnome-software-plugin-flatpak`.
   b. Via apt `sudo apt install gnome-software -y`
9. Installer outil de réglage GNOME via `sudo apt install gnome-tweaks`
10. Installer les codecs et polices multimédias propriétaires via `sudo apt install ubuntu-restricted-extras`
11. Activer _Réduire_ et _Maximiser_ via `gnome-tweaks`

## Sources ISO

1. Version basée sous Ubuntu LTS pour intel/AMD : [Pop!\_OS 22.04 LTS](https://iso.pop-os.org/22.04/amd64/intel/49/pop-os_22.04_amd64_intel_49.iso)
2. Version basée sous Ubuntu LTS pour Nvidia : [Pop!\_OS 22.04 LTS Nvidia](https://iso.pop-os.org/22.04/amd64/nvidia/49/pop-os_22.04_amd64_nvidia_49.iso)
3. Version basée sous Ubuntu LTS pour RAS PI4 : [Pop!\_OS 22.04 LTS RAS PI4](https://iso.pop-os.org/22.04/arm64/raspi/4/pop-os_22.04_arm64_raspi_4.img.xz)
