Oiginate Tile System
=====================
> A modular tile system where tiles can be arranged in seemingly endless combinations. Still in beta.

Tutorial
--------
#### Load in files
Copy the animations.css, animations.js, and tiles.css into your project directory

An example of using the tile system can be found in the tiles.html file

### Usage
____

> All tiles need to be wrapped in a tile-container

#### Rows

> Use the following css classes

Outer tile element
* `main-tile`
  * All tiles need to have this class
* All tiles need to have one of the following classes
  * `tile-fourth`
  * `tile-third`
  * `tile-half`
  * `tile-two-thirds`
  * `tile-three-fourths`
  * `tile-full`
  * `tile-tall`
    * Only to be used with columns


##### Columns
> Wrap element sin a column to make them of height 2 instead of height 1
* `column-half`
* `column-third`
* `column-two-thirds`

>Column fourth looked kind of ridiculous, so I didn't add it in
