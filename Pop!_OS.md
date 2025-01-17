Pop!\_OS

1. Désactiver le secure boot du BIOS
2. Installer Pop!\_OS via clef USB Bootable. Télécharger un iso ci-dessous pour créer la clef bootable :  
   a. Version basée sous Ubuntu LTS pour intel/AMD : [Pop!\_OS 22.04 LTS](https://iso.pop-os.org/22.04/amd64/intel/49/pop-os_22.04_amd64_intel_49.iso)  
   b. Version basée sous Ubuntu LTS pour Nvidia : [Pop!\_OS 22.04 LTS Nvidia](https://iso.pop-os.org/22.04/amd64/nvidia/49/pop-os_22.04_amd64_nvidia_49.iso)  
   c. Version basée sous Ubuntu LTS pour RAS PI4 : [Pop!\_OS 22.04 LTS RAS PI4](https://iso.pop-os.org/22.04/arm64/raspi/4/pop-os_22.04_arm64_raspi_4.img.xz)  
3. Durant installation, possibilité ou non d'encrypter les DD
4. En fin d'installation, redemarrer
5. Configurer ou non les préférences (localisation, keyboard, timezone, privacy, ...)
6. Créer un compte utilisateur local
7. Faire un `sudo apt update && upgrade`
8. Installer ou non snap via `sudo apt install snapd`
9. Configurer ou non snap via `snap install hello-world && hello-world`
10. Installer ou non flatpack via `sudo apt install flatpak`
11. Configurer ou non flatpack via `flatpak remote-add --if-not-exists flathub https://flathub.org/repo/flathub.flatpakrep`
12. Installer GNOME ou non via soit :  
    a. Via Flatpack `sudo apt install gnome-software-plugin-flatpak`.  
    b. Via apt `sudo apt install gnome-software -y`  
13. Installer outil de réglage GNOME ou non via `sudo apt install gnome-tweaks`
14. Installer les codesc et polices multimédias propriétaires via `sudo apt install ubuntu-restricted-extras`
15. Activer _Réduire_ et _Maximiser_ via `gnome-tweaks`
16. Installer PHP et Composer via la CLI de Laravel (ou apt)
17. Installer NodeJS
18. Installer MariaDB
19. Installer VSCode (via flatpack ou apt ou paquet .deb)
20. _DashToPanel_ et _Extensions_ normalement déjà installés

Enjoy it ;)
