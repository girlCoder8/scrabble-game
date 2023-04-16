Scrabble!
========

This is a Swing-based implementation of the Scrabble board game in Java. 
It includes searching and sorting, GUIs,
legal tile placement and scoring algorithms, etc.

## Screenshots

The basic Scrabble UI:
![The basic Scrabble UI](resources/scrabble.png)

Tile placement is checked on each turn. A warning message is displayed when the tile
placement is illegal:
![Illegal tile placement](resources/illegal-tile-placement.png)

It also has a built-in English Scrabble dictionary, which can be enabled or disabled 
during gameplay:
![Dictionary word checking](resources/illegal-word.png)

## How to Use

Download this repository, and navigate to the root directory of the project.
Then use `java -jar dist/scrabble.jar` to run the project.

*Note:* If you aren't in the root projects directory, Java won't be able to find
the files in the resources directory (pictures, dictionary, etc.) so make sure
to run it in the correct location, e.g. from the root directory.
