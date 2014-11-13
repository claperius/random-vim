random-vim
==========

An implementation of [Lehmer's pseudo-random number algorithm](http://en.wikipedia.org/wiki/Lehmer_random_number_generator) in [VimL](https://github.com/trending?l=viml).

Usage
-----

```viml
" echo a random integer in the specified range.
echo Random(1,10)
```

The result will be an integer greater or equal to 1 and less than or equal to 10.

Installation
------------

### With [NeoBundle](https://github.com/Shougo/neobundle.vim)

```viml
NeoBundle 'Claperius/random-vim'
```

### With [VAM](https://github.com/MarcWeber/vim-addon-manager)

```viml
call vam#ActivateAddons(['random-vim'])
```

### With [Vundle](https://github.com/gmarik/Vundle.vim)

```viml
Plugin 'Claperius/random-vim'
```

### With [pathogen](https://github.com/tpope/vim-pathogen)

```sh
cd ~/.vim/bundle
git clone https://github.com/Claperius/random-vim
```

### With [Vimana](https://github.com/c9s/Vimana)

```sh
vimana install gh:Claperius/random-vim
```

### With [Plug](https://github.com/junegunn/vim-plug)

```viml
Plug 'Claperius/random-vim'
```

### With [unbundle](https://github.com/sunaku/vim-unbundle)

```sh
cd ~/.vim/bundle
git clone https://github.com/Claperius/random-vim
```
