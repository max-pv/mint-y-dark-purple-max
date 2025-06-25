# Mint-Y-Purple

This is a default Linux Mint theme with some tweaks that I find necessary for the satisfaction of my inner perfectionist.

## Installation

Install this theme as any regular cinnamon theme. Clone this repo into `./themes` folder, and select the new theme called "Mint-Y-Dark-Purple-Max" in the theme selector of the Cinnamon Themes app.

## Tweaking

If you want to add some more tweaks, you'll need to identify the css selector of the element on the screen that you want to change. For that, press `Alt+F2` and type `lg`, this will open Looking Glass app (aka Developer Tools for Cinnamon). Then go to "Inspect" tab, and in the bottom right corner click the picker button, then click the element you need. This will show the element selector in the Looking Glass app.

Once you know the required selector, open the `cinnamon/cinnamon.css` file, and write stadard (for the most part) CSS code by adding you changes to the bottom of the file, so your changes override default settings. 

When you're done, save file, press `Alt+F2` again, and type `rt` to reload the theme, and you should see your change.