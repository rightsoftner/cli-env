# cli-env

```shell
$ mkdir ~/.config/alacritty
$ cp ./alacrity/alacritty.toml ~/.config/alacritty/alacritty.toml
```

```shell
$ tmux show -g | cat > ./tmux/.tmux.conf
```

## [Alacritty](https://alacritty.org/)

[Fonts](https://www.nerdfonts.com/font-downloads)

|Operation | Key |
|-|-|
|Copy | Control-Alt + C |
|Paste | Control-Alt + P |

## Tmux

[Plugins manager](https://github.com/tmux-plugins/tpm)

```
$ git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```


Reload tmux configuration

```shell
$ run tmux source ~/.tmux.conf
$ run tmux set -g prefix C-a
```
Inside tmux session

```
press the old prefix (CtrlB), :source ~/.tmux.conf
press the old prefix (CtrlB), :set -g prefix C-a
```

| &lt;prefix&gt; | after set new configuration | default |
| - | - | - |
| | Control-A | Control-B |


|Operation | Key | Default key |
|-|-|-|
| Change pane | &lt;prefix&gt; + &larr; &rarr; &uarr; &darr; | &lt;prefix&gt; + &larr; &rarr; &uarr; &darr; |
| Swap panes around| &lt;prefix&gt; + { or }  | &lt;prefix&gt; + { or } |
| Show pane number | &lt;prefix&gt; + q | &lt;prefix&gt; + q |
| Close pane | &lt;prefix&gt; + x | &lt;prefix&gt; + x |
| Open / close pane on full screen | &lt;prefix&gt; + z | &lt;prefix&gt; + z |
| Separate panes to the windows | &lt;prefix&gt; + ! | &lt;prefix&gt; + ! |
| Kill pane | &lt;prefix&gt; + x | &lt;prefix&gt; + x |
| Select window  | &lt;prefix&gt; + [1-9] | &lt;prefix&gt; + [0-9] |
| Go to the previous / next window | &lt;prefix&gt; + p | &lt;prefix&gt; + n |
| Separate window vertical | &lt;prefix&gt; + &#65372; | &lt;prefix&gt; + % |
| Separate window horizontal | &lt;prefix&gt; + - | &lt;prefix&gt; + " |
| Rename window | &lt;prefix&gt; Shift + , | &lt;prefix&gt; + Shift + ,
| Create window | &lt;prefix&gt; + c | &lt;prefix&gt; + c |
| New session | &lt;prefix&gt; + : [new -s my-session] | &lt;prefix&gt; + : [new -s my-session] |
| Select session | &lt;prefix&gt; + s | &lt;prefix&gt; + s |
| Session | &lt;prefix&gt; + Shift + C | &lt;prefix&gt; + Shift + C |
| Fast select session | &lt;prefix&gt; + g | &lt;prefix&gt; + g |
| Next / previous session | &lt;prefix&gt; + ( or ) | &lt;prefix&gt; + ( or ) |
| Whow select tree with sessions, windows and panes | &lt;prefix&gt; + w | &lt;prefix&gt; + w |
|  | Main Copy Mode Keys |  |
| Enter Copy Mode | &lt;prefix&gt; + l | &lt;prefix&gt; + l |
|  | emacs | vi |
| move character    | Up Down Left Right | j k h l       |
| move line         | Ctrl-Up Ctrl-Down  | Ctrl+Y Ctrl+E |
| move whole screen | PageUp PageDown    | Ctrl+B Ctrl+F |
| search            | Ctrl+S             | /             |
| start selection   | Ctrl+Space         | Space         |
| copy selection    | Ctrl+W             | Enter         |
| clear selection   | Ctrl+G             | Escape        |
| exit copy mode    | Escape             | q             |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

$ tmux new -s my-session

$ tmux ls
$ tmux attach -t my-session


## nvim

|Operation | Key | Command |
|-|-|-|
| Undo | u | :u :undo |
| Redo | Ctrl + R | :redo |
|  | 0, $, w,e, b,  | :redo |
|  | gg, G, 7j, 10k, 28G |  |
|  | Insert mode |  |
|  | a, i, o, O |  |
|  | p, P |  |

### Nerd Tree

[How to use NERDTree ](http://www.witkowskibartosz.com/blog/how_to_use_nerdtree.html)

|Operation | Key | Command |
|-|-|-|
| Open NerdTree window |  | :NERDTreeFocus |
| Up to parrent dir | u |  |
| Open menu | m |  |
| Switch betwin file and Nerd Tree | Ctrl + ww |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |



### Config

```shell
$ nvim  ~/.config/nvim/init.vim
```

```
set clipboard=unnamedplus

autocmd BufNewFile *.html 0r ~/.vim/templates/html_main.html
autocmd BufNewFile *.css 0r ~/.vim/templates/css_clean.css
```


### [ripgrep](https://github.com/BurntSushi/ripgrep)

```
$ sudo apt-get install ripgrep
```