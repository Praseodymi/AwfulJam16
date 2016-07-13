Awful Jam 2016
======
Another Thing Name Colbert
------

.gitignore taken from https://github.com/github/gitignore

### Using the level creator

Add a `LevelCreator` to your level and add tiles and offsets to 
`LevelCreator.LevelPieces` and `LevelCreator.LevelPiecesOffset`. It 
*should* select a random tile from the LevelPieces array and place it at 
the root node of the `LevelCreator`. It will then select another tile 
and place it after, repeating up to the value of `LevelTileCount`.
