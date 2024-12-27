# Mod Your Launcher
A guide on creating a launcher modification.
# Notes
⚠️ DO NOT change code. We know that you can find it in there, but we do not endorse it or encourage it. ⚠️
<br>
We are **NOT** responsible for any damages to your Bopimo! account or files.
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
# The Fun Stuff
You can now navigate to your app folder.
<br>
With this, you can change textures.
<br>
Go to renderer\assets\images, and you can change the logos, background, and even the close/minimise buttons!
# Wrapping Up
Are you done and proud of your new creation? Want to actually use it? (WARNING: This will replace your vanilla app.asar with your new modded one. We suggest you back it up somewhere!)
<br>
Back to %appdata%/Bopimo!/Launcher/resources, open a terminal there.
<br>
Run:
<br>
```asar app app.asar```
<br>
Its magic! You can now share it and use it as your actual launcher.
