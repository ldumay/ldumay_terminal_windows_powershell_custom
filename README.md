# LDumay - Personnaliser le Powershell sur Windows ou le Terminal sur Mac OS
 
### 1 - Oh My Posh pour Windows

Source [YouTube - Make Windows PowerShell look Awesome with Themes! | Using Oh My Posh]
(https://www.youtube.com/watch?v=FvHNfpH8fxM)
Site officiel : [https://ohmyposh.dev/](https://ohmyposh.dev/)

#### 1.1 - Installation des Fonts

Téléchargeable [ici](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Meslo.zip)

> Si non, aller sur la partie Fonts de [Oh My Posh](https://ohmyposh.dev/docs/installation/fonts)

Puis configure la police du terminal pour qu'il utilise la police **Meslo LGL NF**.

#### 1.2 - Installation de Oh My Posh 

Ouvrez une invite PowerShell et exécutez la commande suivante :

```
winget install JanDeDobbeleer.OhMyPosh -s winget
```

Cela installe quelques éléments :

- `oh-my-posh.exe` - Exécutable Windows
- `themes` - Les derniers thèmes Oh My Posh

Pour que le `PATH` rechargement soit effectué, un redémarrage de votre terminal est conseillé.

#### 1.3 - Vérifier la présences des thèmes

```
~\AppData\Local\Programs\oh-my-posh\themes

OU

C:\Users\<user>\AppData\Local\Programs\oh-my-posh\themes
```

#### 1.4 - Préparer le lien avec le thème

```
~\AppData\Local\Programs\oh-my-posh\themes\jandedobbeleer.omp.json

OU

C:\Users\<user>\AppData\Local\Programs\oh-my-posh\themes\jandedobbeleer.omp.json
```

#### 1.5 - Activer un thème

Ouvrir le `$PROFILE` de votre terminal :

```
notepad $PROFILE
```

Ajouter dedans :

```
oh-my-posh --init --shell pwsh --config ~\AppData\Local\Programs\oh-my-posh\themes\jandedobbeleer.omp.json | Invoke-Expression
```

Sauvegarder et fermer **notepad**.

Relancer ensuite le terminal.

Et voilà ;)

#### 1.6 - Installer de nouveau thèmes

Pour ajouter un thème, faite la commande `oh-my-posh font install <theme>`.

Exemple :

```
oh-my-posh font install jandedobbeleer
```

### 2 - Oh My Zsh pour Mac OS [non valide encore]

- Source [YouTube - Customize your terminal on MacOS like a pro 🔥 | oh-my-zsh | powerlevel10k | iTerm2](https://www.youtube.com/watch?v=Y9eBohzBcJ8)

#### 1.1 - Installation des Fonts

Téléchargeable [ici](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Meslo.zip)

> Si non, aller sur la partie Fonts de [Oh My Posh](https://ohmyposh.dev/docs/installation/fonts)

Puis configure la police du terminal pour qu'il utilise la police **Meslo LGL NF**.

#### 1.2 - Installation de Oh My Zsh

Ouvrez une invite Termnial et exécutez les commandes suivantes :

```
sh -c "$(curl -fsSL https://raw.github.com/ohmyzsh/ohmyzsh/master/tools/install.sh)"
```

#### 2.2 - Installer un thème

Liste [ici](https://github.com/ohmyzsh/ohmyzsh/wiki/Themes)

#### 2.3 - Désinstaller Oh My Zsh

```
$ sudo chmod 777 ~/.oh-my-zsh/tools/uninstall.sh
$ ~/.oh-my-zsh/tools/uninstall.sh
```


Et voilà ;)













#### 2.6 - Quelques thèmes sympa

Quelques sympa :

- [blue-owl](https://ohmyposh.dev/docs/themes#blue-owl)
![blue-owl](_img/blue-owl.png)

- [blueish](https://ohmyposh.dev/docs/themes#blueish)
![blueish](_img/blueish.png)

- [bubbles](https://ohmyposh.dev/docs/themes#bubbles)
![bubbles](_img/bubbles.png)

- [bubblesextra](https://ohmyposh.dev/docs/themes#bubblesextra)
![bubblesextra](_img/bubblesextra.png)

- [bubblesline](https://ohmyposh.dev/docs/themes#bubblesline)
![bubblesline](_img/bubblesline.png)

- [catppuccin](https://ohmyposh.dev/docs/themes#catppuccin)
![catppuccin](_img/catppuccin.png)

- [cert](https://ohmyposh.dev/docs/themes#cert)
![cert](_img/cert.png)

- [chips](https://ohmyposh.dev/docs/themes#chips)
![chips](_img/chips.png)

- [clean-detailed](https://ohmyposh.dev/docs/themes#clean-detailed)
![clean-detailed](_img/clean-detailed.png)

- [cobalt2](https://ohmyposh.dev/docs/themes#cobalt2)
![cobalt2](_img/cobalt2.png)

- [dracula](https://ohmyposh.dev/docs/themes#dracula)
![dracula](_img/dracula.png)

- [easy-term](https://ohmyposh.dev/docs/themes#easy-term)
![easy-term](_img/easy-term.png)

- [emodipt-extend](https://ohmyposh.dev/docs/themes#emodipt-extend)
![emodipt-extend](_img/emodipt-extend.png)

- [emodipt](https://ohmyposh.dev/docs/themes#emodipt)
![emodipt](_img/emodipt.png)

- [jandedobbeleer](https://ohmyposh.dev/docs/themes#jandedobbeleer)
![jandedobbeleer](_img/jandedobbeleer.png)

- [the-unnamed](https://ohmyposh.dev/docs/themes#the-unnamed)
![the-unnamed](_img/the-unnamed.png)

Liste de thèmes [ici](https://ohmyposh.dev/docs/themes).

---

```
scoop update oh-my-posh
```