# keykosh

Keep your keys in a folder, sealed with one passphrase, so the folder can live in a private git repo

```sh
npm install -g keykosh      # or run it once: npx keykosh ...
keykosh version
```

The first run downloads the keykosh release this package names from GitHub, checks it against the
sha256 pinned in the package, and installs it to `~/.local/bin/keykosh`, where the
[install script](https://github.com/debkosh/keykosh/blob/main/install.sh) puts it. From then on
the binary there (or in `/usr/local/bin`) is the one that runs, and it keeps itself current.

Everything else: https://github.com/debkosh/keykosh
