## シンボリックリンク
- cloneしたら
    - `~/.vimrc` と `/dotfiles/_vimrc` をシンボリックリンクで連動させる
    - $ _ln -sf 現在存在しているファイルまでのパス リンクさせたい場所_

```
$ ln -sf ~/dotfiles/vim/.vimrc ~/.vimrc
```

## プラグイン管理はvim-plugを使用
```
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \ <br>
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
```

- vim-plug(https://github.com/junegunn/vim-plug)
