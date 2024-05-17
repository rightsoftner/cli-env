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
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

$ tmux new -s my-session

$ tmux ls
$ tmux attach -t my-session
