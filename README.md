# Eww Quickstart

## Setup 
```sh
chmod +x ./modules/*.sh
```

Create an `eww` directory in ~/.config and copy the contents of this repo into
it.
```sh
mkdir "$XDG_CONFIG_HOME"/.config/eww
cp -r ./eww.yuck ./eww.scss ./modules "$XDG_CONFIG_HOME"/.config/eww
cmod +x "$XDG_CONFIG_HOME"/.config/eww/modules/*.sh
```

## Running eww
We can run eww with: 
```sh
eww open my-window
```
or 
```sh
eww --config "$XDG_CONFIG_HOME"  open my-window
```

## Other Eww commands
Here's a quick list of useful commands: 
```sh
eww open <window-name>
eww close <window-name>
eww logs
eww kill
```

For more options check the official documentation or run `eww -h`.

## Configuring Eww
`cd` into the configuration directory and take a look. 
```sh
cd "$XDG_CONFIG_HOME"/.config/eww 
```
Start by opening `eww.yuck` and `eww.scss`. You will find comments detailing
the configuration. Feel free to check [the official docs](https://elkowar.github.io/eww) too!

> NOTE: Use `:q` to exit Vim :) (you could always use Nano instead, but we both know that
> you're a cool power user)
```sh
vim eww.yuck
```

## Tips

- You can check the eww logs by running `eww logs`
- You can always use the `--restart` flag to force the daemon to completely restart

## Links 

- Eww: https://github.com/elkowar/eww
- Official Documentation: https://elkowar.github.io/eww
- Some more examples that I've made over time: [eugh](https://github.com/druskus20/eugh)

