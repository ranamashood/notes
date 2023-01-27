# Table Of Content

- [Apps](#apps)

## Apps

- [Audio](#audio)
- [Random](#random)

### Audio

- [qpwgraph](https://github.com/rncbc/qpwgraph) - GUI - A PipeWire Graph Qt GUI Interface

### Random

- [perl-file-mimeinfo](https://archlinux.org/packages/extra/any/perl-file-mimeinfo/) - TUI - Determine file type, includes mimeopen and mimetype

```
# determine a file's MIME type
$ mimetype photo.jpeg
photo.jpeg: image/jpeg

# choose the default application for this file
$ mimeopen -d photo.jpeg
Please choose an application

    1) Feh (feh)
    2) GNU Image Manipulation Program (gimp)
    3) Pinta (pinta)

use application #

# open a file with its default application
$ mimeopen -n photo.jpeg
```
