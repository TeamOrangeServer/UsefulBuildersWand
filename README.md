[![GitHub release](https://img.shields.io/github/release-pre/TeamOrangeServer/UsefulBuildersWand.svg)](https://github.com/TeamOrangeServer/UsefulBuildersWand/releases)[![GitHub release](https://img.shields.io/github/release/TeamOrangeServer/UsefulBuildersWand.svg)](https://github.com/TeamOrangeServer/UsefulBuildersWand/releases)

# UsefulBuildersWand
![Minecraft 1.8.9](https://img.shields.io/badge/Minecraft-1.8.9-yellow.svg?style=flat)
![Minecraft 1.9.4](https://img.shields.io/badge/Minecraft-1.9.4-yellow.svg?style=flat)
![Minecraft 1.10.2](https://img.shields.io/badge/Minecraft-1.10.2-yellow.svg?style=flat)
![Minecraft 1.11.2](https://img.shields.io/badge/Minecraft-1.11.2-yellow.svg?style=flat)
![Minecraft 1.12.2](https://img.shields.io/badge/Minecraft-1.12.2-yellow.svg?style=flat)

## Use paper instead of spigot! !

## Table of Contents

* [About](#about)
* [Contacts](#contacts)
* [License](#license)
* [Downloads](#downloads)
* [Usage](#usage)
* [Issues](#issues)
* [Building](#building)
* [Contribution](#contribution)
* [Localization](#usefulbuilderswand-localization)
* [Credits](#credits)

## About

A Plugin for Builder's Wand from ExtraUtilities

## Contacts

* [GitHub](https://github.com/Team-Fruit/UsefulBuildersWand)

## License

* UsefulBuildersWand
  - (c) 2017 TeamFruit
  - [![License](https://img.shields.io/badge/license-MIT-blue.svg?style=flat)](https://github.com/Team-Fruit/UsefulBuildersWand/blob/master/LICENSE.md)
* Text and Translations
  - [![License](https://img.shields.io/badge/License-No%20Restriction-green.svg?style=flat)](https://creativecommons.org/publicdomain/zero/1.0/)

## Downloads

Downloads can be found on [github](https://github.com/Team-Fruit/UsefulBuildersWand/releases).

## Usage

Change the package name to anything you want and include these files!

## Issues

UsefulBuildersWand crashing, have a suggestion, found a bug?  Create an issue now!

1. Make sure your issue has not already been answered or fixed and you are using the latest version. Also think about whether your issue is a valid one before submitting it.
2. Go to [the issues page](https://github.com/Team-Fruit/UsefulBuildersWand/issues) and click [new issue](https://github.com/Team-Fruit/UsefulBuildersWand/issues/new)
3. Enter your a title of your issue (something that summarizes your issue), and then create a detailed description of the issue.
    * The following details are required. Not including them can cause the issue to be closed.
        * Spigot version
        * UsefulBuildersWand version
        * Crash log, when reporting a crash (Please make sure to use [pastebin](http://pastebin.com/))
            * Do not post an excerpt of what you consider important, instead:
            * Post the full log
        * Other plugins and their version, when reporting an issue between UsefulBuildersWand and another plugin
            * Also consider updating these before submitting a new issue, it might be already fixed
        * A detailed description of the bug or feature
    * To further help in resolving your issues please try to include the follow if applicable:
        * What was expected?
        * How to reproduce the problem?
            * This is usually a great detail and allows us to fix it way faster
        * Screen shots or Pictures of the problem
5. Click `Submit New Issue`, and wait for feedback!

Providing as many details as possible does help us to find and resolve the issue faster and also you getting a fixed version as fast as possible.

## Building

1. Clone this repository via
  - SSH `git clone git@github.com:Team-Fruit/UsefulBuildersWand.git` or
  - HTTPS `git clone https://github.com/Team-Fruit/UsefulBuildersWand.git`
2. Setup workspace
  - Decompiled source `gradlew setupDecompWorkspace`
  - Obfuscated source `gradlew setupDevWorkspace`
  - CI server `gradlew setupCIWorkspace`
3. Build `gradlew build`. Jar will be in `build/libs`
4. For core developer: Setup IDE
  - IntelliJ: Import into IDE and execute `gradlew genIntellijRuns` afterwards
  - Eclipse: execute `gradlew eclipse`

## Contribution

Before you want to add major changes, you might want to discuss them with us first, before wasting your time.
If you are still willing to contribute to this project, you can contribute via [Pull-Request](https://help.github.com/articles/creating-a-pull-request).

The [guidelines for contributing](https://github.com/Team-Fruit/UsefulBuildersWand/blob/master/CONTRIBUTING.md) contain more detailed information about topics like the used code style and should also be considered.

Here are a few things to keep in mind that will help get your PR approved.

* A PR should be focused on content.
* Use the file you are editing as a style guide.
* Consider your feature.
  - Is your suggestion already possible using Vanilla + UsefulBuildersWand?
  - Make sure your feature isn't already in the works, or hasn't been rejected previously.
  - Does your feature simplify another feature of UsefulBuildersWand? These changes will not be accepted.
  - If your feature can be done by any popular plugin, discuss with us first.

Getting Started

1. Fork this repository
2. Clone the fork via
  * SSH `git clone git@github.com:<your username>/UsefulBuildersWand.git` or
  * HTTPS `git clone https://github.com/<your username>/UsefulBuildersWand.git`
3. Change code base
4. Add changes to git `git add -A`
5. Commit changes to your clone `git commit -m "<summery of made changes>"`
6. Push to your fork `git push`
7. Create a Pull-Request on GitHub
8. Wait for review
9. Squash commits for cleaner history

If you are only doing single file pull requests, GitHub supports using a quick way without the need of cloning your fork. Also read up about [synching](https://help.github.com/articles/syncing-a-fork) if you plan to contribute on regular basis.

## UsefulBuildersWand Localization

### English Text

`en_US` is included in this repository, fixes to typos are welcome.

### Encoding

Files must be encoded as UTF-8.

### New Translations

You can provide any additional languages by creating a new file with the [appropriate language code](http://download1.parallels.com/SiteBuilder/Windows/docs/3.2/en_US/sitebulder-3.2-win-sdk-localization-pack-creation-guide/30801.htm).

## Credits

Thanks to

* Notch et al for Minecraft
* Kamesuta for UsefulBuildersWand
* all [contributors](https://github.com/Team-Fruit/UsefulBuildersWand/graphs/contributors)
