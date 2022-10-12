# LDumay - Custom Terminal & Powershell on Windows (and Mac OS - en cours)
 
### 1 - Oh My Posh

Source [YouTube - Make Windows PowerShell look Awesome with Themes! | Using Oh My Posh]
(https://www.youtube.com/watch?v=FvHNfpH8fxM)
Site officiel : [https://ohmyposh.dev/](https://ohmyposh.dev/)

#### 1.1 - Installation des Fonts

Téléchargeable [ici](https://github.com/ryanoasis/nerd-fonts/releases/download/v2.1.0/Meslo.zip)

> Si non, aller sur la partie Fonts de [Oh My Posh](https://ohmyposh.dev/docs/installation/fonts)

Puis configure la police du terminal pour qu'il utilise la police **Meslo LGL NF**.

#### 1.1 - Pré-requis :

- Scoop

#### 1.2 - Installation de Oh My Posh sur Windows

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
~\AppData\Local\Programs\oh-my-posh\themes\sim-web.omp.json

OU

C:\Users\<user>\AppData\Local\Programs\oh-my-posh\themes\sim-web.omp.json
```

#### 1.4 - Activer un thème

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
oh-my-posh font install sim-web
```

#### 1.6 - Quelques thèmes sympa

Quelques sympa :

- [blue-owl](https://ohmyposh.dev/docs/themes#blue-owl)
![blue-owl](https://ohmyposh.dev/assets/images/blue-owl-e9cb9ea32715f6a4e53f9a4f102680eb.png)

- [blueish](https://ohmyposh.dev/docs/themes#blueish)
![blueish](https://ohmyposh.dev/assets/images/blueish-4e0990e623244c530361428348a4b8e0.png)

- [bubbles](https://ohmyposh.dev/docs/themes#bubbles)
![bubbles](https://ohmyposh.dev/assets/images/bubbles-ba044855a85c98c6026a68243fc389ca.png)

- [bubblesextra](https://ohmyposh.dev/docs/themes#bubblesextra)
![bubblesextra](https://ohmyposh.dev/assets/images/bubblesextra-500f0c6708d64349cac09a9e72b5e96e.png)

- [bubblesline](https://ohmyposh.dev/docs/themes#bubblesline)
![bubblesline](https://ohmyposh.dev/assets/images/bubblesline-2db10ee8720ffc8e367539c3626d0a4c.png)

- [catppuccin](https://ohmyposh.dev/docs/themes#catppuccin)
![catppuccin](https://ohmyposh.dev/assets/images/catppuccin-3ff38a555307bb444a79ac77377e9b86.png)

- [cert](https://ohmyposh.dev/docs/themes#cert)
![cert](https://ohmyposh.dev/assets/images/cert-7019406225d324121e953715adc408d4.png)

- [chips](https://ohmyposh.dev/docs/themes#chips)
![chips](https://ohmyposh.dev/assets/images/chips-f71c507a333e5be596e9c38ee600b978.png)

- [clean-detailed](https://ohmyposh.dev/docs/themes#clean-detailed)
![clean-detailed](https://ohmyposh.dev/assets/images/clean-detailed-a734185f883ccd73713bbf826e9636ff.png)

- [cobalt2](https://ohmyposh.dev/docs/themes#cobalt2)
![cobalt2](https://ohmyposh.dev/assets/images/cobalt2-8e6b77eeb233b8fdaf32964fc185ad34.png)

- [dracula](https://ohmyposh.dev/docs/themes#dracula)
![dracula](https://ohmyposh.dev/assets/images/dracula-d55ea32962846aee00f004220fc4490d.png)

- [easy-term](https://ohmyposh.dev/docs/themes#easy-term)
![easy-term](https://ohmyposh.dev/assets/images/easy-term-ebb79f006ebb2f7f18d52ebe6e268426.png)

- [emodipt](https://ohmyposh.dev/docs/themes#emodipt)
![emodipt](https://ohmyposh.dev/assets/images/emodipt-454c672a65575e770777a000eb9892bd.png)

- [sim-web](https://ohmyposh.dev/docs/themes#sim-web)
![sim-web](https://ohmyposh.dev/assets/images/sim-web-2414d65fb11b1c93ec563e95eac4b5dd.png)

- [the-unnamed](https://ohmyposh.dev/docs/themes#the-unnamed)
![the-unnamed](https://ohmyposh.dev/assets/images/the-unnamed-51c8453c6f57a23a4bd89e67c0f922e9.png)

Liste de thèmes [ici](https://ohmyposh.dev/docs/themes).

---

```
scoop update oh-my-posh
```