# yay-aur-helper
Installing and using Yay

## Installing Yay

```sudo pacman -S --needed base-devel git```

```git clone https://aur.archlinux.org/yay.git```

```cd yay```

```makepkg -si```

## Installing AUR packages

Example: Installing brave from AUR

```yay -S brave-bin```

## Keeping packages updated

```yay -Sua```

## Removing packages

Can be removed just like any other software using pacman

```sudo pacman -Rs brave-bin```
