# stylelint-config-wdns

## Installation

```bash
pnpm add -D @wdns/stylelint-config-wdns
```

## Usage

Set your `stylelint` config to:

```json
{
  "extends": ["@wdns/stylelint-config-wdns"]
}
```

### Extending the config

Simply add a `"rules"` key to your config, then add your overrides and additions there.


```json
{
  "extends": ["@wdns/stylelint-config-wdns"],
  "rules": {
    
  }
}
```

## Dependencies
 
[Stylelint](https://stylelint.io/)  
[@stylistic/stylelint-plugin](https://github.com/stylelint-stylistic/stylelint-stylistic)  
[stylelint-config-recommended-scss](https://github.com/stylelint-scss/stylelint-config-recommended-scss)  
[stylelint-config-standard](https://github.com/stylelint/stylelint-config-standard)  
[stylelint-order](https://github.com/hudochenkov/stylelint-order)  
[stylelint-scss](https://github.com/stylelint-scss/stylelint-scss)

## Change Log
 
[CHANGELOG](CHANGELOG.md)

## License

Copyright (c) 2023 WebDevNerdStuff  
Licensed under the [MIT license](LICENSE.md).
