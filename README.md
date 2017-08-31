# TAO PCI training

To get this extension in your TAO installation, modify your root composer.json as follow:

## 1. Add the repository
```
"repositories": [
    ...,
    {
       "type": "vcs",
       "url": "https://github.com/iskawata/kwt001pci.git"
    }
],

```

## 2. Add the extension
```
require" : {
    ...,
    "iskawata/kwt001pci": "dev-develop"
],

```

## 3. Update composer
```
composer update --prefer-source