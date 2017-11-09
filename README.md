# pound.syntax

### Syntax hightlight for mcedit (Midnight Commander built-in file editor) for [Pound] configuration file (pound.cfg)

To add syntax hightlighting for the **Pound** config file (usually located at `/etc/pound/pound.cfg`) do the following:

1) Edit the file `/usr/share/mc/syntax/Syntax` adding to it this two lines:

```
file .\*pound.cfg$ Pound\config
include pound.syntax
```    

2) [Download] the `pound.syntax` file from this repository and place it to `/usr/share/mc/syntax/`

That's all!
Enjoy :)

[Pound]: http://www.apsis.ch/pound/
[Download]: https://raw.githubusercontent.com/tumick/pound.syntax/master/pound.syntax
