Dokku Root Config Plugin
========================
This is a very simple Dokku plugin that prevents any user except root from accessing app configuration options.

**Note:** This isn't secure unless you use it alongside [dokku-rootplugin](https://github.com/directactioneverywhere/dokku-rootplugin) to disable normal users from managing plugins!

Installation
------------

    sudo dokku plugin:install https://github.com/directactioneverywhere/dokku-rootconfig.git

License
-------
This work is free. You can redistribute it and/or modify it under the terms of the Do What The Fuck You Want To Public License, Version 2, as published by Sam Hocevar. See the COPYING file for more details.
