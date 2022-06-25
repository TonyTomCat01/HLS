# HLS

A custom statically build of haskell-language-server version 1.7.0 for ghc 9.0.2. You may ask, 'Why a git repo for a custom build? you could build it afterwards if you want'. Because building it sucks!. It took me two weekends to figure it out and about 6 hours to build it, yes I 
have a slow machine and I definitely don't want to build it "afterwards". So if you need the language server and you are on Arch linux (important) and want a statically linked executable (very important), don't get sucked (very very important).

Quick front note:
  this build does not have any formatter plugins, floskell, fourmolu, all the formatters. If you want a formatter you should download it manually and use it with formatter.nvim for neovim, because we know that true programmers use vim/neovim or emacs probably :).
