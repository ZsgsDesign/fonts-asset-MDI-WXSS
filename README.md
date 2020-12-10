# fonts-asset-MDI-WXSS
MDI-WXSS for Composer.

## Install

```bash
composer require oomphinc/composer-installers-extender
composer require fonts-asset/mdi-wxss
```

And in `composer.json`:

```json
    "extra": {
        "installer-types": [
            "fonts-asset"
        ],
        "installer-paths": {
            "public/fonts/{$name}": [
                "type:fonts-asset"
            ]
        }
    },
```

## Usage

```html
<link rel="stylesheet" href="/fonts/mdi-wxss/MDI.css">
```

## Credit

[Material Design Icon](https://github.com/ZsgsDesign/Material-Design-Icon)