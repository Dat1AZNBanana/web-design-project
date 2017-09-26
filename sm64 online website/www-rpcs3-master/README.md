![Preview](https://raw.githubusercontent.com/DAGINATSUKO/www-rpcs3/master/public_docs/preview.png)

## RPCS3.net
Official source code for [rpcs3.net](https://rpcs3.net "RPCS3 Homepage") orginally forked from my own website, [daginatsuko.com](https://daginatsuko.com "DAGINATSUKO Homepage"). This website is designed to house and promote the progress of RPCS3, an open-source PlayStation 3 emulator and debugger built for Windows and Linux. At its core, this website aims to deliver a lightweight user experience that purely focuses on the content and technical aspects of the project and ensures the viewer can easily access its content on demand.

## Licensing
RPCS3.net uses the GNU General Public License Version 2.0 (June 1991). According to the license, you are welcome to use the website and its source code for any purpose, but distributing the websites' files requires that the source code be released and attribution given. For more details on how the GNU General Public License system works, please refer to [GNU.org](https://GNU.org)

## Independencies
The RPCS3.net [Compatibility List](https://github.com/AniLeo/rpcs3-compatibility "RPCS3 Compatibility List repository") by [AniLeo](https://github.com/AniLeo "AniLeo's GitHub Profile") allows users to sort listed games by status, first character, region, last update date or by typing the games ID or title in the searchbox as well as order listed games by ID, Title, commit, status or last update date both asynchronously and desynchronously. Users won't have to search exactly by a game's title to find it in the database.

The Levenshtein string comparisons ensures that the closest game is returned when no results are found and abbreviated search allows the user to search for games using abbreviations.

#### Proprietary Technologies
* Milk UX Engine Lite by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* Compatibility DB by [AniLeo](https://github.com/AniLeo "AniLeo's GitHub Profile")

#### Web Technologies
* HTML 5.0
* CSS 3.0
* PHP 5.5
* jQuery 3.2.0
* MySQL

#### External Resources
* [Flaticon](http://www.flaticon.com "Flaticon")
* [JS Cookie](https://github.com/js-cookie/js-cookie "JS Cookie")
* [Animate.css](https://daneden.github.io/animate.css "Animate.css")
* [Animated Waves](https://jsfiddle.net/loktar/M9Brh/ "Animated Waves")

#### Target Platforms
* [Google Chrome](https://www.google.com/chrome/browser/desktop/)
* [Google Chromium](https://www.chromium.org/Home)
* [Microsoft Edge](https://www.microsoft.com/en-us/windows/microsoft-edge)
* [Apple Safari](https://www.apple.com/safari/)
* [Mozilla Firefox](https://www.mozilla.org/en-US/firefox/new/)
* [Opera Software Opera](http://www.opera.com/)

## Development
Your only requirement is [Docker](http://docker.com/getdocker)!

To run the application, just do:

```shell
docker-compose up
```

Then browse to [localhost:8080](http://localhost:8080)!

## Deployment
Simply download the repository files and upload them to your web server or open them in a text editor, preferably [Notepad++](https://notepad-plus-plus.org/). Based on the web server, RPCS3.net comes pre-defined as a SSL (Secure Sockets Layer) website. This may cause issues with web servers or web server emulators that do not have SSL capabilities. To fix this issue, .htaccess must be modified accordingly.

For the [Compatibility List](https://github.com/AniLeo/rpcs3-compatibility "RPCS3 Compatibility List repository") portion of the website, simply place files inside the lib/compat directory within the website's source code.

## History
* 01-15-2017 - tkoham offers a Patreon initiative for RPCS3 on [January 15th, 2017](https://github.com/RPCS3/rpcs3/issues/2263)
* 01-20-2017 - DAGINATSUKO joins the RPCS3 team on [January 20th, 2017](https://github.com/RPCS3/rpcs3/issues/2263)
* 01-20-2017 - RPCS3.net foundation forked from undisclosed project by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 01-20-2017 - RPCS3.net project started by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 01-21-2017 - RPCS3.net launched and published by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 01-22-2017 - RPCS3.net compatibility launched and published by [AniLeo](https://github.com/AniLeo "AniLeo's GitHub profile")
* 01-25-2017 - RPCS3.net blog launched by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 04-26-2017 - RPCS3.net Manta UX Lite port started by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 05-01-2017 - RPCS3.net Alpha 1 launched by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 08-02-2017 - RPCS3.net Alpha 2 launched by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")
* 08-04-2017 - Development improvements with Docker from [Jake Hamilton](https://github.com/jakehamilton "Jake Hamilton's GitHub profile")
* 09-01-2017 - RPCS3.net Beta 1 launched by [DAGINATSUKO](https://github.com/DAGINATSUKO "DAGINATSUKO's GitHub profile")

## Copyright
All trademarks and copyright-written content found on this website belong to their respective owners. The RPCS3 team is in no way affiliated with Sony or PlayStation. 

The "PlayStation logo", "PlayStation 3 logo", "PlayStation 4 logo", "PlayStation Portable logo", "PlayStation Vita logo", "PlayStation Move logo", "PlayStation Network logo", "PlayStation Store logo", "PlayStation Plus logo", "Sony logo", "Sony Computer Entertainment logo" and their aforementioned names are registered trademarks of Sony Computer Entertainment Inc. "Sony Entertainment Network" is a trademark of Sony Corporation. Library programs are copyright Sony Interactive Entertainment Inc.
