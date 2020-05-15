## Screenshot Uploader
A simple bash script for uploading screenshots to ShareX custom uploaders

## Usage:
Using [maim](https://github.com/naelstrof/maim):
```bash
$ maim | ./uploader
```
Using [shotgun](https://github.com/neXromancers/shotgun):
```bash
$ shotgun - | ./uploader
```

## Setup:
Change the `config_location` variable in `uploader` to the path of your config file. Optionally, you can pass the path to a different config file as the first argument of the script `uploader $HOME/config.sxcu`

## Requirements:
- A screenshot tool
  - [maim](https://github.com/naelstrof/maim)
  - [shotgun](https://github.com/neXromancers/shotgun)
- [xclip](https://github.com/astrand/xclip)
- [ripgrep](https://github.com/BurntSushi/ripgrep)
