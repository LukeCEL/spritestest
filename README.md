# spritestest
This is a test for [Celestia](https://github.com/CelestiaProject/Celestia) 1.7.0 development. Specifically, it is meant to test issue [#549](https://github.com/CelestiaProject/Celestia/issues/549): Stars becoming yellow.

## License
Everything in this repository is under public domain. 

The sprite texture, called 27px.png, was made using Microsoft Word. I created a 1 inch wide white circle, and set its soft edges to 27px. An earlier version of the sprite texture, called blob.png, was courtesy of Cham.

## Usage
To use this test package, simply clone the repository and move the entire thing to the "extras" repository of your Celestia installaion.

There are two objects that can be used to test this issue. The first is circumstellardisk.ssc, which contains a sprite-based model defined by a SSC file. The second is disktest.dsc, which contains a sprite-based model defined by a DSC file.