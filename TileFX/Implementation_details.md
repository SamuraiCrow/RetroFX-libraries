Step 1:  Convert ScrollingTrick sources to shared library.

Step 2:  Add BOB/VSprite support with multi-region clipping.  (This is NOT optional because the ScrollingTrick algorithm introduces a Copper seam that allows wrap around from the bottom to the top of the screen buffer to save Chip RAM.)

Step 3:  switch Copper handler to allow rainbows

Step 4:  make Amos extension as frontend and create simple examples

Step 5:  AGA version of the same

Stretch goal 1:  add TOME features like animated tile support and multi-tile Briks, then update the extension and make example AMOS codes to demonstrate the capabilities

Stretch goal 2:  CPU blitting for Fast RAM tile access and faster BOBs on 68020+ while possibly adding PowerBobs extension compatibility

Stretch goal 3:  Adapt to allow tiled dual playfield support

~~Stretch goal 4:  sidebar “screen” support using sprite hardware~~ moved to separate project

Stretch goal 5:  Mesa version for AROS graphics card users

Stretch goal 6:  MiniGL/TinyGL version for NextGen Amiga-like systems without requiring an emulator

Stretch goal 7:  OpenGL/latest Mesa version for Mac/Linux/Windows systems (depends on stretch goal 5 or 6 being met successfully).
