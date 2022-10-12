# ldumay_terminal_windows_powershell_custom
 
### 1 - Oh My Posh

Source [https://www.youtube.com/watch?v=FvHNfpH8fxM](https://www.youtube.com/watch?v=FvHNfpH8fxM)
Site officiel : [https://ohmyposh.dev/](https://ohmyposh.dev/)

#### 1.1 - Pré-requis :

- Scoop

#### 1.2 - Installation de Oh My Posh sur Windows

Ouvrez une invite PowerShell et exécutez la commande suivante :

```
scoop install https://github.com/JanDeDobbeleer/oh-my-posh/releases/latest/download/oh-my-posh.json
```

Cela installe quelques éléments :

- `oh-my-posh.exe` - Exécutable Windows
- `themes` - Les derniers thèmes Oh My Posh

Pour que le `PATH` rechargement soit effectué, un redémarrage de votre terminal est conseillé.

#### 1.2 - Ajuter un thème à Oh My Posh

Pour ajouter un thème, faite la commande `oh-my-posh font install <theme>`.

Exemple :

```
oh-my-posh font install sim-web
```

Quelques sympa :

- [blue-owl](https://ohmyposh.dev/docs/themes#blue-owl)
![blue-owl](https://ohmyposh.dev/assets/images/blue-owl-ee4fe94f97b271d66611eac650791ae2.png)

- [blueish](https://ohmyposh.dev/docs/themes#blueish)
![blueish](https://ohmyposh.dev/assets/images/blueish-12c7f06b59801a09b7cfa36c3d85011a.png)

- [bubbles](https://ohmyposh.dev/docs/themes#bubbles)
![bubbles](https://ohmyposh.dev/assets/images/bubbles-ba044855a85c98c6026a68243fc389ca.png)

- [bubblesextra](https://ohmyposh.dev/docs/themes#bubblesextra)
![bubblesextra](https://ohmyposh.dev/assets/images/bubblesextra-500f0c6708d64349cac09a9e72b5e96e.png)

- [bubblesline](https://ohmyposh.dev/docs/themes#bubblesline)
![bubblesline](https://ohmyposh.dev/assets/images/bubblesline-2db10ee8720ffc8e367539c3626d0a4c.png)

- [catppuccin](https://ohmyposh.dev/docs/themes#catppuccin)
![catppuccin](https://ohmyposh.dev/assets/images/catppuccin-d2efc8c07178308a62abbc4405f5ae5c.png)

- [cert](https://ohmyposh.dev/docs/themes#cert)
![cert](https://ohmyposh.dev/assets/images/cert-3ceb4e9ce324f06ef7d3e9b35a832ca5.png)

- [chips](https://ohmyposh.dev/docs/themes#chips)
![chips](https://ohmyposh.dev/assets/images/chips-df53239162ce3a9adb2fdee9847920a8.png)

- [clean-detailed](https://ohmyposh.dev/docs/themes#clean-detailed)
![clean-detailed](https://ohmyposh.dev/assets/images/clean-detailed-29e022b1e550116a8773b774e35e597e.png)

- [cobalt2](https://ohmyposh.dev/docs/themes#cobalt2)
![cobalt2](https://ohmyposh.dev/assets/images/cobalt2-8e6b77eeb233b8fdaf32964fc185ad34.png)

- [dracula](https://ohmyposh.dev/docs/themes#dracula)
![dracula](https://ohmyposh.dev/assets/images/dracula-1f0e0da0fa27161230a9aaaab0a4adb1.png)

- [easy-term](https://ohmyposh.dev/docs/themes#easy-term)
![easy-term](https://ohmyposh.dev/assets/images/easy-term-8cee7e254318b9cf5943a73c43a7d57a.png)

- [emodipt](https://ohmyposh.dev/docs/themes#emodipt)
![emodipt](https://ohmyposh.dev/assets/images/emodipt-a0d4dee73ff102c08c4a90d11b41e4a8.png)

- [sim-web](https://ohmyposh.dev/docs/themes#sim-web)
![sim-web](https://ohmyposh.dev/assets/images/sim-web-2414d65fb11b1c93ec563e95eac4b5dd.png)

- [the-unnamed](https://ohmyposh.dev/docs/themes#the-unnamed)
![the-unnamed](https://ohmyposh.dev/assets/images/the-unnamed-51c8453c6f57a23a4bd89e67c0f922e9.png)

Liste de thèmes [ici](https://ohmyposh.dev/docs/themes).

---

```
scoop update oh-my-posh
```