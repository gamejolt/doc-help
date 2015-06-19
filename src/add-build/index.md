# Adding builds/files to my game page

If your game is Complete or Canceled, then you are required to upload a build.

If your game is a Work-in-Progress, but you have some sort of playable build (alpha, beta, prototype, etc.), we encourage you to upload it.

You can also upload additional files for your game--anything from a level pack to a PDF manual, etc.

## How do I add a build or file?

When you're ready to add a game build or an additional file to your game page, go to your [developer dashboard](http://gamejolt.com/dashboard/) and select a game from under "Your Games". You will be taken to the game's overview page, where you can edit and manage all aspects of your game. Visit the "Builds & Files" tab, then select "Add Package" to get started.

When you add builds, you must first create a package to contain them. Once you have a package, you will add a new release to it, and then you will add any builds of the current version of your game. Don't worry; it sounds more complicated than it is. 

The basic flow is Add Package-->Add Release-->Add Build.

## Packages

Packages are how games are distributed on Game Jolt. Packages contain releases, which in turn contain builds or additional files.

The first package you make becomes your main package and should contain your game build(s). The main package will always hold the most current builds of your game. Every time you upload a newer build, you should add a new release to this package.

If you want to distribute an alternate build of your game (for example, one without cinematics to make it a lighter download), you can create a new package for it.

If you are uploading an additional file that is not a build, you should create a new package for it. 

### Package names and descriptions

Every package needs a name. Your main package should be named after your game, since that's what it contains. Other packages should be named appropriately; for example, "Game Art Book" for an art book, or "Level Pack 1" for a level pack.

The description field should generally be left blank, but it's there just in case the package's name is not enough to distinguish it from other packages on the page. Please only fill it in if it's absolutely necessary.

## Releases

Once you have a package, you can add releases to it. Releases are important because they let us--and players--access the latest version of your game.

Add a new release whenever you want to upload an updated build (or an updated additional file).

**Important:** Releases start out hidden by default, so when you're ready for your builds to become active and accessible on your game page, you must publish them!

### Version numbers 

Just like packages have names, releases have version numbers.

On Game Jolt, version numbers adhere to the [SemVer specifications](http://semver.org/). The basic idea is to start with version 0.1.0 and increment to 1.0.0, which should be the release of the completed game. You can keep the versioning that simple or you can get fancy and add extensions to the numbers.

MAJOR.MINOR.PATCH is the format of SemVer numbers. You can follow this as closely as you want, but, according to the specifications:
- A new MAJOR version indicates incompatible API changes,
- A new MINOR version indicates new functionality that's backwards-compatible,
- A new PATCH version indicates only backwards-compatible bug fixes.

There are several valid extensions to the MAJOR.MINOR.PATCH format, but a couple of especially useful ones are -alpha and -beta. Using these, you could do something like 0.5.0-alpha, then 0.5.0-beta, and finally 0.5.0. A version with an extension is considered earlier than one without, so in our example, 0.5.0 would be the latest version. 

## Builds and files

Now that you've created a package and a release, you are ready to upload your builds or additional files. A release can contain one file, one build, or multiple builds for different platforms. So, for example, your release version 0.1.0 might contain builds for Windows, Mac, and Linux, as well as a browser build. Note that one release cannot contain two two different builds for the same platform.

If you are uploading a new port of your game for another platform, simply add a new build to the appropriate release. If, however, you are updating builds across all supported platforms, you should add a new release to the package.

[What types of builds/files can I upload?](/build-types/index.md)

[How do I publish my game?](/publish-game/index.md)

[How do I edit/manage my game?](/manage-game/index.md)

[How do I add my game to Game Jolt?](/add-game/index.md)
