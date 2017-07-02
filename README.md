# Syntax highlighting files for GNU/Nano [nanorc](https://nanorc/)

This repository contains some manually written syntax highlighting files for the [GNU/Nano editor](https://nano-editor.org/).

Some files also come from the default Nanu installation.

## Install with git :wrench:
Be sure you don't have a directory `~/.nano` and no file `~/.nanorc`.

Then, clone the repository and symlink the config file:
```bash
git clone https://github.com/Naereen/nanorc.git ~/.nano/
ln -s ~/.nano/.nanorc ~/.nanorc
```

You can try to check if the installation went well by opening the `~/.nanorc` file.

```bash
nano  ~/.nanorc  # should be nicely colored!
```

> **Warning**: clearly, this will only work on GNU/Linux. And I only tested it on Ubuntu...

## Install manually
You can download and install any of the `LANGUAGEXXX.nanorc` files, where you wish, and be sure that your `~/.nanorc` file include the files you want, with this syntax:

```python
# Coloration for nanorc, from https://github.com/Naereen/nanorc
include "~/.nano/nanorc.nanorc"
```

----

## :scroll: License ? [![GitHub license](https://img.shields.io/github/license/Naereen/nanorc.svg)](https://github.com/Naereen/nanorc/blob/master/LICENSE)
[MIT Licensed](https://lbesson.mit-license.org/) (file [LICENSE](LICENSE)).
© [Lilian Besson](https://GitHub.com/Naereen), 2017.

[![Maintenance](https://img.shields.io/badge/Maintained%3F-yes-green.svg)](https://GitHub.com/Naereen/nanorc/graphs/commit-activity)
[![Ask Me Anything !](https://img.shields.io/badge/Ask%20me-anything-1abc9c.svg)](https://GitHub.com/Naereen/ama)
[![Analytics](https://ga-beacon.appspot.com/UA-38514290-17/github.com/Naereen/nanorc/README.md?pixel)](https://GitHub.com/Naereen/nanorc/)
[![BADGINATOR](https://badginator.herokuapp.com/Naereen/nanorc.svg)](https://github.com/defunctzombie/badginator)
[![Awesome Badges](https://img.shields.io/badge/badges-awesome-green.svg)](https://github.com/Naereen/badges)

[![ForTheBadge built-with-swag](http://ForTheBadge.com/images/badges/built-with-swag.svg)](https://GitHub.com/Naereen/)
[![ForTheBadge uses-badges](http://ForTheBadge.com/images/badges/uses-badges.svg)](http://ForTheBadge.com)
