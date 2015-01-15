# Vim Plugins that I use

So I don't have to set this up on multiple computers

# Getting Started

``` shell
# Install Pathogen

mkdir -p ~/.vim/autoload ~/.vim/bundle && \
curl -LSso ~/.vim/autoload/pathogen.vim https://tpo.pe/pathogen.vim

# Adding in the Plugins
cd ~/.vim/bundle 
git clone git@github.com:clintonhalpin/vim-plugins.git .

# Fetch the submodules
git submodule update --init

```

# Add .vimrc

[Vimrc File](https://gist.github.com/clintonhalpin/12f583c709a6fca7ab63)
