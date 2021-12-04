# kissvim
> Keep It Simple, Stupid!

![](https://img.shields.io/tokei/lines/github/arebaka/kissvim)
![](https://img.shields.io/github/repo-size/arebaka/kissvim)

A keymap for normal & visual modes of the Vim to make it easy.  
This keymap gives you the ability to edit your configs with one left hand.  
The right hand at this time can be lowered under the table to edit something else more.

```
,---,---,---,---,---,---,---,---,---,---,---,---,---,------,
| ` | 1 | 2 | 3 | 4 | 5 | 6 | 7 | 8 | 9 | 0 | - | = |  <-  |
|---'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,----|
| ->| | ⇤ | ↑ | ⇥ | ↺ | ⤓ | ↷ | ↶ |   |   |   |   |   | \  |
|-----',--',--',--',--',--',--',--',--',--',--',--',--'----|
| Caps | ← | ↓ | → | ⌖ | ➠ |   | J |   |   |   |   | Enter |
|------'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-,-'-------|
| shift  | ⌧ | ✂ | © | ➤ | ⌦ |   |   | ? | / | : |   shift |
|------,-'-,-'---|---'---'---'---'---'---',--'--,'--,------|
| ctrl |   | alt |                        | alt |   | ctrl |
'------'   '-----'------------------------'-----'   '------'
```

## general
| new | old | hint |
| --- | --- | ---- |
| `/` | `:` | like slashtags in Telegram and some games |
| `>` | `/` | forward search |
| `<` | `?` | reverse search |

> as is:  
> `` . , ' " ; - + _ = ` ~ ! @ # $ % ^ & * \ ( ) [ ] { } ``  
> `` n N m `` (search & marks)  
> `` g G ``

## navigation (normal & visual)
| new | old | hint |
| --- | --- | ---- |
| `a` | `h` | wasd as in some games |
| `d` | `l` | |
| `w` | `k` | |
| `s` | `j` | |

| new | old | hint |
| --- | --- | ---- |
| `A` | `b` | WASD |
| `D` | `w` | |
| `W` | `Ctrl+b` | |
| `S` | `Ctrl+f` | |

| new | old | hint |
| --- | --- | ---- |
| `Z` | `H` | ZXC |
| `X` | `M` | |
| `C` | `L` | |

| new | old | hint |
| --- | --- | ---- |
| `Ctrl+a` | `0` | |
| `Ctrl+d` | `$` | |

## select
| new | old | hint |
| --- | --- | ---- |
| `f` | `v` | |
| `F` | `V` | |
| `Ctrl+f` | `Ctrl+v` | |

## undo/redo
| new | old | hint |
| --- | --- | ---- |
| `u` | `u` | as is |
| `U` | `U` | as is |
| `y` | `Ctrl+r` | as in some GUI programs |

## insert
| new | old | hint |
| --- | --- | ---- |
| `q` | `i` | to the left of WASD |
| `e` | `a` | to the right of WASD |
| `r` | `r` | as is |
| `t` | `o` | |

| new | old | hint |
| --- | --- | ---- |
| `Q` | `I` | |
| `E` | `A` | |
| `R` | `R` | |
| `T` | `O` | |

## edit (normal & visual)
| new | old | hint |
| --- | --- | ---- |
| `z` | `d` | zxc |
| `x` | `c` | |
| `c` | `y` | |

> `zz`, `xx`, and `cc` are available

| new | old | hint |
| --- | --- | ---- |
| `v` | `p` | to the right of zxc |
| `b` | `x` | backspace |

| new | old | hint |
| --- | --- | ---- |
| `V` | `P` | |
| `B` | `X` | |

| new | old | hint |
| --- | --- | ---- |
| `j` | `J` | |

## autocomplete (insert)
| new | old | hint |
| --- | --- | ---- |
| `Ctrl+Space` | `Ctrl+n` | |

## exit (all modes)
| new | old | hint |
| --- | --- | ---- |
| `Ctrl+x` | `:q` in normal | |

## tab (visual)
| new | old | hint |
| --- | --- | ---- |
| `Tab` | `>` | |
| `Shift+Tab` | `<` | |

## moving lines (all modes)
| new | old | hint |
| --- | --- | ---- |
| `Ctrl+w` | `:m -2` in normal | |
| `Ctrl+s` | `:m +1` in normal | |
