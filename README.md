## シンボリックリンク
cloneしたら
~/.vimrcと/dotfiles/_vimrcをシンボリックリンクで連動させる
$ ln -sf 現在存在しているファイルまでのパス リンクさせたい場所

`
$ ln -sf ~/dotfiles/vim/.vimrc ~/.vimrc
`

## プラグイン管理はvim-plugを使用
`
$ curl -fLo ~/.vim/autoload/plug.vim --create-dirs \
    https://raw.githubusercontent.com/junegunn/vim-plug/master/plug.vim
`
vim-plug:https://github.com/junegunn/vim-plug
