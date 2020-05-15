## Screenshot Uploader
A simple bash script for uploading screenshots to ShareX custom uploaders

## Usage:
Using [maim]():
  ```bash
$ maim | ./uploader
```
Using [shotgun]():
```bash
$ shotgun - | ./uploader
```

## Setup:
Change the `config_location` variable in `uploader` to the path of your config file. Optionally, you can pass the path to a different config file as the first argument of the script `uploader $HOME/config.sxcu`
