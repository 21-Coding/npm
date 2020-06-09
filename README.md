<iframe src="https://giphy.com/embed/ayQ99hp01HFN6" width="480" height="376" frameBorder="0" class="giphy-embed" allowFullScreen></iframe><p><a href="https://giphy.com/gifs/hd-ayQ99hp01HFN6">via GIPHY</a></p>


### run the following commands

### this next line removes all the existing global npm packages
## `rm -rf /usr/local/lib/node_modules`

### remove previously installed node
## `brew uninstall node`

### clean all broken symlinks
## `brew prune`

### always a good idea to have the latest version of Homebrew
## `brew update`

### install node via Homebrew, but without npm
### there are two options:
#### - if you want to use `yarn` (yarnpkg.com), you need latest 'node'
#### - if you don't use `yarn` (yarnpkg.com), prefer LTS 'node@6'

## `brew install node --without-npm`

### this next step is optional
### install yarn (see yarnpkg.com for more info)

## `brew install yarn`

### follow up with: https://yarnpkg.com/en/docs/install
