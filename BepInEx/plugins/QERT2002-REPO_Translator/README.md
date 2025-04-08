# REPO_Translator
A mod for R.E.P.O. that can apply manual translation to the game on selected language.

- При стандартной установке игра будет переведена на русский!
- By default installing, the game will be on russian language!

## MANUAL TRANSLATE

Initially, the plugin translates the game into Russian language.

But if you want, you can translate it into almost any language following these instructions:
- Install the mod and run game one time.
- Close your game.
- Go to config and change TranslatorDevModeEnabled to true.
- Go to config and change SelectedTranslate to abbreviation of your language.
- Save the config file and run game.
- Play the game for 10-15 minutes, trying to get all possible variations of the text, press the buttons in the menu, start up and wander around a little, aim at different objects.
- Close the game.
- Go to plugins/REPO_Translator/ folder, in it you will see the file Translate_yourlang.xml
- Open the file, in it you will see many lines like key="blabla" translate="blabla"
- Change the translate="blabla" into your own language on every line, example: <Translate key="Start Game" translate="Start game" /> -> <Translate key="Start Game" translate="Начать игру" />
- After that, save the file and open the game.
- You will see that all the lines that you translated are displayed in your language.
- If there are some lines left without translation, check your file, perhaps you forgot to translate them, if there is no line in the file - alas, most likely it is a picture or dynamic text.
- When you are happy with the result, close the game, open the config and set TranslatorDevModeEnabled to false and now you can play the game in your favorite language.
- If you want, you can send the translation file with the config file to your friends and play together.

## Installation

- Install [BepInEx](https://thunderstore.io/c/repo/p/BepInEx/BepInExPack/)
- Unzip this mod into your `REPO/BepInEx` folder

Or use the thunderstore mod manager to handle the installing for you.

## Configuration

- In the BepInEx config folder, you can find com.github.qert2002.REPO_Translator.cfg and enable or disable DEVMODE