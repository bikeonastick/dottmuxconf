# My .tmux.conf

These settings are great. They've been picked up from around the web and my
tmux setup is something I want to be able to recreate easily, if need be.
Also, if anyone else can benefit from seeing these in one place, all the
better. 

I spend a lot of time in vim, so my brain and fingers are kind of broken. To
keep my terminal navigation productivity up, I've added these things to my
tmux configuration to improve my life. You'll notice that most of these
additions are vim-influenced. 

## Installation instructions

1. clone this repository
1. initialize and update submodules

   `git submodule init`
   `git submodule update`

1. create the ~/.tmux directory and link your local plugins dir into it

   ```
   mkdir ~/.tmux
   ln -s `pwd`/plugins ~/.tmux/plugins
   ```

1. link the tmux.conf in this repo to .tmux.conf in your homedir

   `ln -s ~/dottmuxconf/tmux.conf ~/.tmux.conf` 

1. If tmux is already running, reload your conf:

    `<leader>: source-file ~/.tmux.conf` 

1. Install plugins for tmux per the [tmux plugin manager docs](https://github.com/tmux-plugins/tpm) `ctrl` + `b` + `I`

## License

This project is released under the [MIT](http://opensource.org/licenses/MIT) 
license.

Copyright © 2013 robert tomb
