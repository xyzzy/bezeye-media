# Welcome to the Wonderful World of Bezeye

This project contains the media files for project bezeye [https://github.com/xyzzy/bezeye](https://github.com/xyzzy/bezeye)

# Requirements

* `gcc` or compatible
* `libgd` for 2d graphics support [https://libgd.github.io](https://libgd.github.io)
* `mootools` for the scoreboard GUI [https://mootools.net](https://mootools.net)
* `php` for scripts
* `ffmpeg` (optional) for comparison

# Building

- Prepare `bezeye` project

    cd <pathToBezeye>
    ./autogen.sh

- Configure/Build bezeye project in media directory

    <pathToBezeye>/configure
    make
    make all-sbs

Then add referenced media to project

# Versioning

Using [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/xyzzy/bezeye-media/tags).

# License

This project is licensed under the GNU General Public License v3 - see the [LICENSE.txt](LICENSE.txt) file for details
