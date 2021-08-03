# Getting Started

## Steps

- Clone
- Create fonts / Copy fonts to `data/fonts` folder
- Generate Sprites to `data/sprites` folder using `@mapbox/spritezero-cli`
- Create / Copy tiles to `tiles/` folder
- Update your config.json to point to the styles and tiles as appropriate

#### TODO: Expound the instructions

## Generate sprites

- Install [spritezero-cli](https://github.com/mapbox/spritezero-cli) 

- Put all your icons in the icons folder. `NOTE:` The file name will be the icon's name without the .svg extension

- Run the following commands from the root directory

```
cd data/sprites
spritezero sprite ../../icons
spritezero --retina sprite@2x ../../icons

```
