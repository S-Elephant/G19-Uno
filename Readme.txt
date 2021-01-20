===============================================================================
Installation Instructions
===============================================================================
If you have the .NET framework 4.0 then you can just start the application.
Any up2date Windows PC should have it.

If you do not have it installed then install the .NET framework 4.0 from here:
http://www.microsoft.com/download/en/details.aspx?id=17851

Note that it requires Windows Media Player for it's sound playback. But unless
you manually de-installed it, it should just work fine.

===============================================================================
About G19 - Uno
===============================================================================
Written by: Squirting Elephant (A.k.a Kernel-Density, Napoleonite, Silver)

A simple card game to play on the G19 keyboard. Now you have something to do
while you are loading or waiting for other players.

Features:
- Between 1-5 AI players (+1 Human player)
- Adjustable Rules (ingame options)
- Other adjustable options
- A started game may be resumed from the main menu (does not work if the game
  shut down)
- You can use your own sound fx and graphics by replacing the images in the
  "Textures" and "Audio" folders.
- Special cards: wild 4, wild, draw 2, reverse, rotate cards, skip turn.
- Uses about 26kb RAM (no soundfx and music) or ~34kb when playing music.

===============================================================================
Manual
===============================================================================
- Use the Left/Right directional buttons to cycle through your cards.
- Use the Up/Down directional buttons to draw a card or skip a turn.
- Press [OK] button to play the selected card or to confirm a choice.
- Press the [Cancel] button (ingame) to return to the main menu.
- Use the Windows System Tray Icon to configure or exit the game.
- You can replace the music in the Audio\Music\ folder with your own. Like
  the Tripple Triad theme from Final Fantasy VIII. Sadly I am not allowed to
  distribute such songs. Make sure to keep the filename and extension the
  same.

AI settings:

Easy:
- Will randomly play cards and chose random colors for it's wild cards.

Normal:
- Will play the number card of which it has the most of it's color-kind.
- Will chose it's wild card colors based on the cards it has and will
  only play them when the next player in line has 1 card left or when it can't
  play any other cards anymore.
- When the rules prohibit finishing with wildcards then the AI will play the
wild card when it has only a single non-wild-card left.

Hard:
- Sorry, not yet implemented.

==============================================================================
Known bugs & issues:
==============================================================================

Bugs:
- The LCDMON process crashes after a certain amount of idle time.

Issues:
- Something goes wrong with the selection rendering width on the left side
  of the selected menu choice.

==============================================================================
Version History:
==============================================================================

Version 1.00 (April 12 2012):
  - First release.

Version 1.01 (April 14 2012)
	- Fixed the turn direction texture.