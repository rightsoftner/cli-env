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

| &lt;prefix&gt; | after configuration | default |
| - | - | - |
| | Control-A | Control-B |


|Operation | Key | Default key |
|-|-|-|
| Select window  | &lt;prefix&gt; + [1-9] | &lt;prefix&gt; + [0-9] |
| Select session | &lt;prefix&gt; + s | &lt;prefix&gt; + s |
| Separate window vertical | &lt;prefix&gt; + &#65372; | &lt;prefix&gt; + % |
| Separate window horizontal | &lt;prefix&gt; + - | &lt;prefix&gt; + " |
| Session | &lt;prefix&gt; + Shift + C | &lt;prefix&gt; + Shift + C |
| Fasr select session | &lt;prefix&gt; + g | &lt;prefix&gt; + g |
| Rename window | &lt;prefix&gt; Shift + , | &lt;prefix&gt; + Shift + ,
| Create window | &lt;prefix&gt; + c | &lt;prefix&gt; + c |
| Next / previous session | &lt;prefix&gt; + ( or ) | &lt;prefix&gt; + ( or ) |
| Change pane | &lt;prefix&gt; + &larr; &rarr; &uarr; &darr; | &lt;prefix&gt; + &larr; &rarr; &uarr; &darr; |
| Swap panes around| &lt;prefix&gt; + { or }  | &lt;prefix&gt; + { or } |
| Show pane number | &lt;prefix&gt; + q | &lt;prefix&gt; + q |
| Open / close pane on full screen | &lt;prefix&gt; + z | &lt;prefix&gt; + z |
| Separate panes to the windows | &lt;prefix&gt; + ! | &lt;prefix&gt; + ! |
| Kill pane | &lt;prefix&gt; + x | &lt;prefix&gt; + x |
| New session | &lt;prefix&gt; + : [new] | &lt;prefix&gt; + : [new] |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |
|  |  |  |

$ tmux new -s my-session


