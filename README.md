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

## ghc extentions
* https://downloads.haskell.org/~ghc/master/users-guide/glasgow_exts.html
* https://github.com/shiatsumat/wiwinwlh-jp/wiki/言語拡張

## build

```sh
stack build
stack build --fast --file-watch
stack exec hello-hs-exe
```
