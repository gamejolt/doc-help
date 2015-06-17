# What types of builds/files can I upload?

Game Jolt supports both downloadable games and browser-based games. What files you upload depend on what kind of build you have.

## Downloadable/Desktop

If your game is downloadable, you should generally compress your game files into a single .zip file and upload that. Whether you've got an installer, a stand-alone application, a complex system of folders, or anything in between, zip it all up. If your build is a single file, zipping it is unnecessary. When you upload the build, choose the platform/operating system on which it runs (Windows, Linux, Mac, or Other).

When adding a downloadable build, here's something to keep in mind: The more steps a gamer has to go through in order to play your game, the less likely they are to actually play it.

For example: If you made your game in LOVE or Pygame, compile an executable build rather than expecting players to already have downloaded and installed what they need to run it. If you made your game in RPG Maker, don't expect everyone to go through the extra work of installing a runtime package or a new font.

## Browser/Web

If your game runs in a browser, with or without a plugin, the type of file you upload depends on the kind of build you have. The most popular types of browser builds on the site are HTML, Unity, and Flash, although you can also upload Java applets and Silverlight applications (if you must). When you upload your browser build, you will be asked to specify type of build, as well as the game's width and height in pixels.

### HTML

HTML games can be played in any modern browser without any plugins, and they can be enjoyed on many mobile devices. If you're adding an HTML build, upload a .zip file containing the index.html file and all the files and assets necessary to run the game.

### Unity

If your Unity build is meant to be downloaded, you should upload a .zip file containing an application file and a data folder.

If you're adding a browser build meant to be played using the Unity Webplayer plugin, you should upload a single .unity3d file. You may also want to disable right click behaviour by ticking the checkbox.

### Flash

If you are adding a game to be played in browsers equipped with the Adobe Flash Player plugin, upload a single .swf file.

### Java

You can upload a Java applet as a downloadable file and you can also upload it as a browser build. Either way, you can upload a single .jar file. For a web build, you'll need to specify the main Java class name.

### Silverlight

Silverlight was essentially Microsoft's answer to Adobe's Flash, only it never really caught on and now it's been deprecated by the company. Game Jolt doesn't want to stop supporting any old games on the site, so you can technically still upload Silverlight games. You'll need to upload a .xap file, which is just a renamed .zip file that contains an "AppManifest.xaml" file and any DLL files required by the application.

### Supplemental and Other Files

These are completely unnecessary, but frequently awesome, and they really show that the developer has gone that extra mile. You can upload any kind of zipped files you want as "Other" builds, like manuals, maps, charts, comics, Infocom-style feelies, a print-and-play adaptation, or anything else you can think of that's not a game or music file.

[Adding builds/files to my game page](add-build/index.md)

[How do I unhide/hide game builds?](unhide-build/index.md)

[How do I edit/manage my game?](/edit-game/index.md)
