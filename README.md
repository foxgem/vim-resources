vim-resources
=============

my vim configuration

1. In your home dir(for windows, the home dir is c:/Users/your\_name), create a repo for bundles: 
   - git clone https://github.com/gmarik/vundle.git .vim/bundle/vundle. 
1. (This step is Windows specific) copy curl.cmd to %Git\_Home%\cmd
1. In your .vimrc, include the following two lines
   - source .../vim-resources/.vimrc.my
   - source .../vim-resources/.vimrc.my.bundle
1. Open Vim, then type ":BundleInstall" to install bundles
