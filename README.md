# peichi-ssh
## Usage

```
bash <(curl https://github.com/jertban/peichi-ssh/blob/master/key.sh) -g jertban -d
```

## Options

`-o` - Overwrite mode, this option is valid at the top

`-g` - Get the public key from GitHub, the arguments is the GitHub ID

`-u` - Get the public key from the URL, the arguments is the URL

`-l` - Get the public key from the local file, the arguments is the local file path

`-d` - Disable password login
