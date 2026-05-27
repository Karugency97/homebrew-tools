# karugency/homebrew-tools

Homebrew tap for Karugency CLI tools.

## ⚠️ Note sur `secib`

La formule `secib` cible le repo **privé** `Karugency97/secib-cli`. Homebrew n'a pas de mécanisme natif pour télécharger les release assets d'un repo privé. **`brew install karugency97/tools/secib` échouera tant que le repo `secib-cli` reste privé.**

Si tu as accès au repo, utilise l'install manuel décrite dans le [README de secib-cli](https://github.com/Karugency97/secib-cli#installation) (via `gh release download` ou build depuis la source).

La formule reste publiée ici pour : (1) être prête si le repo devient public un jour, (2) servir de référence pour `goreleaser` qui auto-update la formule à chaque release.

## Available formulas

- `secib` — CLI Go pour le gateway NPL SECIB (https://github.com/Karugency97/secib-cli) — _install manuel actuellement requis_
