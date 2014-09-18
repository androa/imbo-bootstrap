Imbo Bootstrap
==============

Used to quickly set up your own Imbo installation. For information about Imbo,
go see the [main project page](https://github.com/imbo/imbo).

Installation / Usage
--------------------

1. Download the [`composer.phar`](https://getcomposer.org/composer.phar)
   executable or use the installer:

    ``` sh
    $ curl -sS https://getcomposer.org/installer | php
    ```

2. Install with Composer:

    ``` sh
    $ php composer.phar create-project --no-interaction \
        androa/imbo-bootstrap /path/to/install
    ```

3. Optional: Open your favourite editor and remove the
   `post-create-project-cmd` scripts, they are no longer needed.

**IMPORTANT:** Rename the name in composer.json before adding it to your own source
code version system!

License
-------
Copyright (c) 2011-2014, André Roaldseth <andre@roaldseth.net>

Licensed under the MIT License

Community
---------
If you have any questions feel free to join `#imbo` on the Freenode IRC
network (`chat.freenode.net`), or ask them on the
[forum](https://groups.google.com/forum/#!forum/imbo-project).
