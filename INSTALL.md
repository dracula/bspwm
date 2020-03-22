### [bspwm](https://github.com/baskerville/bspwm)

#### Test first

You can easily test the theme, without the need to change and reload your [bspwm](https://github.com/baskerville/bspwm) config, by issuing four commands in your favorite terminal

```
bspc config normal_border_color "#44475a"
bspc config active_border_color "#bd93f9"
bspc config focused_border_color "#ff79c6"
bspc config presel_feedback_color "#6272a4"
```

You could also use **Cyan** as your _focus_ color and the **Comment** color for your _active_  node border.
_Active means, the node is the focused one on an unfocused monitor_

```
bspc config active_border_color "#6272a4"
bspc config focused_border_color "#8be9fd"
```

#### Make it permanent

To make it permanent, add the four lines mentioned in the previous section to your `bspwmrc`, which you can probably find under `~/.config/bspwm/bspwmrc` and reload [bspwm](https://github.com/baskerville/bspwm)

```
bspc wm -r
```
