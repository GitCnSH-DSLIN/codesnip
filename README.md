# CodeSnip

A code bank designed with Pascal in mind.

## Overview

CodeSnip is an open source code bank for storing and viewing your code snippets. While it can manage snippets in any source language, it is focussed mainly on Pascal and Delphi code for which additional features are available.

CodeSnip also provides offline access to the DelphiDabbler [Code Snippets Database](http://snippets.delphidabbler.com/).

The program is available in both standard and portable editions.

For more information see [http://codesnip.delphidabbler.com/features](http://codesnip.delphidabbler.com/features).

CodeSnip requires Windows 2000 or later and Internet Explorer 6 or later, although XP and IE 8 and later are preferred.

## Installation

CodeSnip is installed and removed using a standard Windows installer. Administrator privileges are required for installation.

## Bugs & Feature Requests

Bugs can be reported using the [Bug Tracker](https://sourceforge.net/p/codesnip/bugs/) on SourceForge. Info on how best to report bugs is provided on the tracker.

Feature requests can be made on the [Feature Request Tracker](https://sourceforge.net/p/codesnip/feature-requests/) on SourceForge. Once again info on how to proceed is provided.

> In time the bug and feature request trackers will be moved to GitHub.

## Support

There's quite a lot of support available for CodeSnip:

* A comprehensive help file.
* A [read-me file](https://raw.githubusercontent.com/delphidabbler/codesnip/master/Docs/ReadMe.txt)<sup>*</sup> that discusses installation, configuration, updating and known issues.
* A dedicated set of [web pages](http://delphidabbler.com/url/codesnip-home).
* An [FAQ](http://wiki.delphidabbler.com/index.php/FAQs/CodeSnipAppUsing).
* A [discussion group](https://sourceforge.net/p/codesnip/discussion) on SourceForge (albeit barely used!).
* An [RSS news feed](http://delphidabbler.com/feeds/site-news-feed?id=codesnip). This can also be accessed via the program.
* A [Google+ page](https://plus.google.com/u/0/b/108251259814638768561/108251259814638768561/posts).
* A [Blog](http://codesnip-app.blogspot.co.uk/).
* A [privacy statement](https://raw.githubusercontent.com/delphidabbler/codesnip/master/Docs/Privacy.txt)<sup>*</sup> that provides information about any personal information stored by the program and what info is transmitted over the net.

There's also plenty of info available on how to compile CodeSnip from source - see below.

<sup>*</sup> These links take you to the most recent version of the documents -- they can change from release to release.

## Source Code

Up to and including release 4.13.1 the project's source code was maintained in a Subversion repository on [SourceForge](https://sourceforge.net/p/codesnip/code/). The Subversion repo was converted to Git on 21 5 October 2015 and imported to GitHub. All releases from v3.0.0 are marked by tags in the form `version-x.x.x` where `x.x.x` is the version number.

> Note that any branches that were created and deleted in the Subversion repo are missing from the Git history. So, for full details of the the project's history from v3.0.0 to v4.13.1 please refer to the old Subversion repo on SourceForge.

Following tag `version-4.13.1` the [Git Flow](http://nvie.com/posts/a-successful-git-branching-model/) methodology was adopted, with the exception that development work on CodeSnip v5 exists outside Git Flow in the `pagoda` branch (See below for details).

Up to and including release 4.13.1, `master` is simply a copy of the old Subversion `trunk` and, as such, contains various development commits along with numerous commits related to management of Subversion. After release 4.13.1, and the addition of this read-me file, `master` contains only commits relating to an actual release.

### Contributions

Contributions are welcome. Just fork the repo and create a feature branch off the `develop` branch. Commit your changes to your feature branch then submit a pull request when ready.

If you are contributing to CodeSnip 5 development please create your feature branch off the `pagoda` branch instead.

### Compiling

`master` and each branch will have a file in the root directory named `Build.html` that gives detailed information about how to compile CodeSnip.

There is also a [FAQ](http://wiki.delphidabbler.com/index.php/FAQs/CodeSnipAppSource).

## Change Log

The program's current change log can be found in the file `Docs/ChangeLogs/ChangeLog-v4.txt` on the `master` branch.

## License

The program's EULA which gives full details of the license applying to the latest release can be found in the file `Docs\License.html` in the `master` branch. The license has changed between releases, so if you need to see an older one, select the appropriate `version-x.x.x` tag and read the older version of the file.

Most of the original code is made available under the [Mozilla Public License v2](https://www.mozilla.org/MPL/2.0/).

The [CodeSnip Compiling & Source Code FAQ](http://wiki.delphidabbler.com/index.php/FAQs/CodeSnipAppSource) may be useful if you have any queries about re-using CodeSnip source in other projects.

## CodeSnip 5 Development

Following a false start back in 2013/4 in the `parsnip` branch, development of CodeSnip 5 has restarted. The code can be found in the `pagoda` branch, which picks up where `parsnip` left off. (Don't ask where those names came from!)

At present the direction CodeSnip is being taken is to:

1. Generalise it to be a code bank for several different languages instead of just Pascal, while still providing some additional support for test-compiling Pascal code.
2. Increase the focus on the user's own code while downplaying the importance of code downloaded from the DelphiDabbler [Code Snippets database](http://snippets.delphidabbler.com/). This will still be available but will be very much an add on, like [SWAG](http://swag.delphidabbler.com/) is at present.
3. Remove the program's dependency on web services provided by [DelphiDabbler.com](http://delphidabbler.com) given the current uncertainty over that websites future.

Comments on these ideas are welcome - just create a [feature request](https://sourceforge.net/p/codesnip/feature-requests/) and select the `v5 (pagoda)` milestone.

## Donate

If you've found the program useful please consider making a donation to help cover costs. Donations are accepted by [PayPal](http://delphidabbler.com/url/donate-cs) in British Pounds (GBP) -- [see  common exchange rates](http://www.xe.com/currency/gbp-british-pound).
