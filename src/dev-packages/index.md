---
title: Packages, Releases and Builds Guide
---

# Builds/Files

Builds and packages are how you organize and distribute your game's files for people to play and download.

Games that are marked as Complete or Canceled must have builds uploaded. Work-in-Progress games are only encouraged to add builds once they have something playable.

You can also upload additional, non-playable files for your game as "other" builds. These could be things like level editors, map packs, PDF manuals, etc.

## Packages

Packages allow you to bundle your game files on your game page. For example, if you have a server application, you may want to distinguish it from your main game. Or if you have an art pack, you can package that up separately.

You can add multiple builds to a package for all the different platforms your game runs on. That way, you don’t have to create a different package for each platform.

Packages contain versioned releases so that gamers can easily identify the latest builds available within a package as well as see the release history.

## Releases

Releases communicate that new versions of the builds in your package are available.

We provide you metrics per release so you can measure the success of your current and past releases (*and future!*).

Remember that you can add multiple builds in a release. If you're adding game files, make sure to add builds for all the platforms your game runs on in a single release. Only create a new release if you have a new version of the package.

**Important:** Releases start out hidden by default, so when you're ready for your builds to become active and accessible on your game page, you must publish them!

## Release version numbers

Just like packages have names, releases have version numbers. Version numbers are in the format MAJOR.MINOR.PATCH. Example: 1.2.0

In general...

- A new MAJOR version indicates a major release such as an official launch, new sequel, etc.

- A new MINOR version indicates updates such as new features, additional content, graphical updates, etc.

- A new PATCH version indicates smaller changes such as bug fixes, hotfixes balancing, etc.

While your game is in development, consider starting with a small version number such as 0.1.0 or even 0.0.1. This will allow you to grow your version number for new releases during development without it getting too large.

If you're releasing your game's first stable package, consider labeling it 1.0.0. This usually signals to users that it's stable and ready to play. You can still release new updates by using the MINOR and PATCH values, such as 1.0.1 or 1.2.0.

Version number formats adhere to the [SemVer specifications](http://semver.org/). You can read the specs for more information on the formatting of version numbers.

## Builds and files

Builds are the files that you upload into your packages. They can be either downloadable game files, browser-based game files, or additional files such as art packs, source code, PDFs, etc.

For downloadable builds, you must set the platform(s) that they run on. You can only have one build for each platform within a release. If you'd like to add another build for the same platform, you probably want to make a new release or package. If your build isn't an application, but instead an additional downloadable file such as a PDF or archive of images/music, select the "Other" platform. You can add as many "Other" builds as you'd like within a release.

Browser builds allow you to upload your game for a certain embeddable browser technology such as HTML games, Flash, Unity, etc. You can only add one of each browser type within a release.

### Launch Options

Launch options let us know how to run the executable file for your build. In most situations we are able to auto-detect what they are, but sometimes we need your help.

They are only required for downloadable builds with a platform selected (Windows, Mac or Linux).

If your build is an executable such as a `.exe` file, we will detect it as a standalone executable. However, if it's an archive such as a `.zip` file, we will try guessing which file within the archive is your application. If we can't, or if we guess incorrectly, you will have to let us know the path to the executable in the archive.

