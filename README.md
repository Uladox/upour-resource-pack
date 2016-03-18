# Upour resource pack for Solarus

This repository provides musics, sounds, tilesets and sprites
from Upour
for the
[Solarus engine](https://github.com/christopho/solarus).

You can use these resources if you want to develop a game with the
Solarus engine using Upour graphics.

Feel free to contribute!

## Create a new quest with Upour resources

Using the Upour resource pack in a new quest is straightforward.

- Create a new quest with [Solarus Quest Editor](http://www.solarus-games.org/development/quest-editor]).
- Close the quest editor.
- Copy the content of this repository's `data` directory into the `data`
  directory of your quest, overwriting the existing `project_db.dat` file.

## Integrate Upour resources into an existing quest

This might be quite tedious if your quest already has resources with the same
id as resources of this pack.
In future versions of Solarus Quest Editor, an import feature
will make the process easier.
Here is how to proceed:

- Make a backup of your quest.
- Copy the content of this repository's `data` directory into the `data`
  directory of your quest, except `project_db.dat`.
- `project_db.dat` is the list of resources of your quest.
  Append the text of `project_db.dat` of this repository into your own
  `project_db.dat`. Make sure there are no duplicated ids.


