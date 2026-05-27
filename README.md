# karugency/homebrew-tools

Homebrew tap for Karugency CLI tools.

## Usage

```bash
brew tap karugency97/tools
brew install karugency97/tools/secib
```

⚠️ **Authentification requise** — les binaires `secib` sont hébergés sur un repo GitHub **privé** (`Karugency97/secib-cli`). Avant `brew install`, exporter un PAT GitHub avec scope `repo` :

```bash
export HOMEBREW_GITHUB_API_TOKEN=ghp_xxxxxxxxxx
brew install karugency97/tools/secib
```

Persister dans `~/.zshrc` ou `~/.bash_profile` pour les futures installs. **Ne pas committer ce token**.

Sans le token, l'install échoue avec `Download failed: ... 404`.

### Alternative — install manuel

Si l'install Homebrew ne convient pas, télécharger directement les binaires depuis https://github.com/Karugency97/secib-cli/releases/latest et placer dans le `PATH`. Voir le [README de secib-cli](https://github.com/Karugency97/secib-cli#installation) pour les étapes détaillées.

## Available formulas

- `secib` — CLI Go pour le gateway NPL SECIB (https://github.com/Karugency97/secib-cli)
