# hello-hs

## vscode
* https://qiita.com/waddlaw/items/b83cd10311200095fe87

```sh
git clone https://github.com/haskell/haskell-ide-engine
cd haskell-ide-engine
stack install
```

```sh
stack install hoogle --install-ghc
hoogle --version
hoogle generate
```

## watch build
```sh
stack build --fast --file-watch
```