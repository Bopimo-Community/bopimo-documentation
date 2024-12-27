# Mod Your Launcher
A guide on creating a launcher modification.
# Unpacking
To get the ability to modify files in the launcher, you need to install Electron's asar package:
<br>
```npm install @electron/asar```
<br>
Then, run
<br>
```npm update```
<br>
You can now use asar!
<br>
Navigate to %appdata%/Bopimo!/Launcher/resources
<br>
Open a terminal in that folder you just went to
<br>
Run:
<br>
```asar extract app.asar app```
<br>
This will extract your app.asar to a folder named app.
