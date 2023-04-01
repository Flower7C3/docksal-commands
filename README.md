# Docksal custom commands

## Installation

1. Install [Docksal](https://docksal.io/installation) on local computer
2. Get custom commands:

```
bash <(curl -fsSL https://raw.githubusercontent.com/Flower7C3/docksal-custom/master/install)
```

## Available commands

* `init-gulp` - install valid NPM via NVM, install all NVM resources, install `gulp` and `gulp-cli`
* `gulp` - run gulp on CLI container
* `npm` - run npm on CLI container
* `open` - open **http://${VIRTUAL_HOST}** URL in browser
* `opens` - open **https://${VIRTUAL_HOST}** URL in browser
* `m` - shortcut for `mutagen` command ([see Mutagen for Docksal](https://github.com/nicoschi/mutagen-for-docksal))
