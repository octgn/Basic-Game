# Basic-Game
A basic OCTGN game plugin to be used as a starting point for new developers to build games with. 

Please refer to our [documentation](https://github.com/octgn/OCTGN/wiki#create-games-on-octgn) to get started with this package.

# Requirements

## ID's
All of our ID's are GUID's(a .net variation of UUID's). It stands for Globally Unique ID. No two games can use the same ID's, this is very important.

For all sample ID's in this game, please use [https://www.guidgenerator.com/](https://www.guidgenerator.com/) to generate unique ID's
Do *NOT* under *ANY* circumstances make up your own ID's without using the tool above, it is *NOT* and will *NEVER* be supported.

The current ID's that will need to be changed are as follows:

    SAMPLEID-GUID-0000-0000-00000000GAME
    SAMPLEID-GUID-0000-0000-000000000SET
    SAMPLEID-GUID-0000-0000-0000000CARD1

## definition.xml

You *must* replace the following items
* ID (see above)
* Game Name
* Game Version
* Game Url - this MUST NOT be linked to octgn.net, it must be a site in which the users of your game can get in contact with you with issues they might have. We very often point users to the game developers for support with their games, and it is your responsibility if you release a game.
* Authors - Just names of people involved with the game
* Description - Brief bit of info about your game

## set.xml

You *must* replace the following items
* ID
* Game ID
* Version
* Set Name
* Card ID
