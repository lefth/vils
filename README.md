This little script enables you to "edit an ls",
i.e. it will load a list of filenames into your
favorite editor (presumably vi). Any changes to
the filenames will result in renaming the respective
files.

Notes:

- Do not change the numbers in the first column,
  unless you know exactly what you're doing.
- If you remove an entire line, the corresponding
  file will _not_ be deleted.  It just remains
  untouched.
- You can use any character in filenames, with one
  special case:  backslashes have to be specified
  twice.
- If there are any filename collisions, you will
  be asked if overwriting the first file is OK.
- Do not try to exchange the filenames of two or
  more files.  It won't work.
- If you want to edit the filenames of certain
  files only, you can specify them on the command
  line (the default is `*`).

## Authorship

Original author: Oliver Fromme <olli@fromme.com>

Oliver's version can be found here:
https://www.freshports.org/sysutils/vils/

This modernized version is by Daniel Zwell.

License: BSD

## Alternatives

Simon Schiele ported the original script to bash and added additional options:
https://github.com/simonschiele/vils-ng

Another script called "vidir" is part of the moreutils package. I do not
recommend it, as its interface leads to accidental file deletion.
