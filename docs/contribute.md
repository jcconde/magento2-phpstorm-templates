# Contribute

## Fork and Install this project

**IMPORTANT:** Before you do this, make sure PhpStorm is not running, or it will overwrite the changed files before shutting down.

1.- Clone this repo.

```
git clone https://github.com/staempfli/magento2-phpstorm-templates.git
```

2.- Set Symlinks to new templates:
 
**OS X**

```
ln -s $(PWD)/magento2-phpstorm-templates/Preferences/templates/* ~/Library/Preferences/<product name><version number>/templates/
```

**Linux**

```
ln -s $(PWD)/magento2-phpstorm-templates/Preferences/templates/* ~/.<product name><version number>/config/templates/
```
or
```
ln -s $(PWD)/magento2-phpstorm-templates/Preferences/templates/* /snap/phpstorm/current/config/templates/
```

## Create new Templates

### Live templates:

0. Add new live templates on PHPStorm within the ***StmpflMagento2*** group.
0. Commit, push and create PR

### File Template:

0. Create new File template on PHPStorm
0. Copy this template from your local PHPStorm preferences into this project `Preferences/fileTemplates`
0. Commit, push and create PR