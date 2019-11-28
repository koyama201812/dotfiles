## シンボリックリンク
- cloneしたら
    - `~/.vimrc` と `/dotfiles/_vimrc` をシンボリックリンクで連動させる
    - $ _ln -sf 現在存在しているファイルまでのパス リンクさせたい場所_

```
$ ln -sf ~/dotfiles/vim/.vimrc ~/.vimrc
```

## プラグイン管理はvim-plugを使用
```
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

- vim-plug(https://github.com/junegunn/vim-plug)

## プラグイン(32)

1. NERDTree
    - ディレクトリツリーを表示する
    - 開く：`Ctrl + E`

2. Commentary
    - コメントアウト：`gcc`

3. Fugitive
    - Gitコマンドを簡単に実行
    - :Git add `:Gwrite`
    - :Git checkout `:Gread`
    - :Git rm `Gremove`

4. Auto-pairs
    - 括弧など入れると自動で閉じ括弧出す
