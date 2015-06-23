# Builds/Files

If your game is Complete or Canceled, then you are required to upload a build.

If your game is a Work-in-Progress, but you have some sort of playable build (alpha, beta, prototype, etc.), we encourage you to upload it.

You can also upload additional files for your game--anything from a level pack to a PDF manual, etc.

## How do I add a build or file?

In order to add a build you will need to add a game through your [developer dashboard](http://gamejolt.com/dashboard/) or click into an existing game. Then follow the 3 steps below:

- **Add a Package** -- Create a package for your game files, level editor, map pack, extensions, art pack, etc. 

- **Add a Release** -- Releases house versions of your builds. Create a release for the first version of your game, the second, the third, etc. 

- **Add a Build** -- Builds are your downloadable or browser files.

## Packages

Packages help categorize and distinguish your game pack from other files such as art packs, etc. If all you have are your game files, then follow the above 3 steps. But if you have other packages such as level editors, map paccks, etc. you’d like to add to your page, then you can create a package for each and label them accordingly! 

## Releases

Once you have a package, you can add releases to it. Releases are important because they house all versions, archived and new of your game’s builds. You can now have all of your game’s builds in one place with version numbers that communicate the latest build from the oldest!

Add a new release whenever you want to upload an updated build (or an updated additional file).

**Important:** Releases start out hidden by default, so when you're ready for your builds to become active and accessible on your game page, you must publish them!

## Version numbers

Just like packages have names, releases have version numbers.

On Game Jolt, version numbers adhere to the [SemVer specifications](http://semver.org/). The basic idea is to start with version 0.1.0 and increment to 1.0.0, which should be the release of the completed game. You can keep the versioning that simple or you can get fancy and add extensions to the numbers.

MAJOR.MINOR.PATCH is the format of SemVer numbers. You can follow this as closely as you want, but, according to the specifications:

- A new MAJOR version indicates incompatible API changes,
- A new MINOR version indicates new functionality that's backwards-compatible,
- A new PATCH version indicates only backwards-compatible bug fixes.

There are several valid extensions to the MAJOR.MINOR.PATCH format, but a couple of especially useful ones are -alpha and -beta. Using these, you could do something like 0.5.0-alpha, then 0.5.0-beta, and finally 0.5.0. A version with an extension is considered earlier than one without, so in our example, 0.5.0 would be the latest version.

## Builds and files

Now that you've created a package and a release, you are ready to upload your builds or additional files. A release can contain one file, one build, or multiple builds for different platforms. So, for example, your release version 0.1.0 might contain builds for Windows, Mac, and Linux, as well as a browser build. Note that one release cannot contain two different builds for the same platform.

If you are uploading a new port of your game for another platform, simply add a new build to the appropriate release. If, however, you are updating builds across all supported platforms, you should add a new release to the package.
