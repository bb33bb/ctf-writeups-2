# Maze Adventure

We get a packaged application. Unpack using 7zip, then unpack asar file with npx. We can modify renderer.js, which contains some of the source code of the game. In particular, the powerup costs and flag costs are hardcoded in the array `const _0x1dd28a=[0x64,0x3e8,0x7fffffff];`. We can change this to $0, then play the game and get free walk-speed and timer upgrades. Complete all three mazes manually and we get the flag.
