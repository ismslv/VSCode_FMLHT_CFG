# FMLHT CFG

## Features

The language support for FMLHT studio inner config files.

To use with https://github.com/ismslv/Unity_CFG (of version > 1.2)

## Release Notes

```
#Config.fmcfg

BoardSize = 10:10 #Size of the board: width, height
TurnsTotal = 128
HeroName = "Captain Jack"
HeroStartHealth = 0.1:0.9
```

To be able to fold a region of settings:

```
#> World options
Option1 = 1
Option2 = 2.1
#<
```

You can use the following snippets:

`region` for regions

`spell` for spells (refer to Unity CFG for usage)


### 0.0.8

Spells and highlighting

### 0.0.7

Initial release of FMLHT Config