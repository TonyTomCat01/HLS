# HLS

A custom static build of [haskell-language-server](www.github.com/haskell/haskell-language-server) version 1.7.0 for ghc 9.0.2. You may ask, 'Why a git repo for a custom build? you could build it _afterwards_ if you want'. Because building it sucks!. It took me two weekends to figure it out and about 6 hours to build it, yes I 
have a slow machine and I definitely don't want to build it _afterwards_. So if you need the language server and you are on Arch linux (important) and want a statically linked executable (very important), don't get sucked (very very important).

### __Quick side note__:
  * this build does not have any formatter plugins, [floskell](https://github.com/ennocramer/floskell), [fourmolu](https://github.com/fourmolu/fourmolu), all the formatters.
  * If you want a formatter you should download it manually and use it with [formatter.nvim](https://github.com/mhartington/formatter.nvim) for [neovim](https://github.com/neovim/neovim). 
  * true programmers use only vim/neovim.
