Dokku Root Config Plugin
========================
This is a very simple Dokku plugin that prevents any user except root from accessing app configuration options.

**Note:** Currently this isn't secure, because non-root users [can still manage plugins](https://github.com/directactioneverywhere/dokku-rootconfig/issues/2), meaning they could just disable this plugin then access config. If you use this version you will also want to disable users from managing plugins. That might become baked into this or made a separate plugin in a future release.

Installation
------------

    sudo dokku plugin:install https://github.com/directactioneverywhere/dokku-rootconfig.git

License
-------
Copyright © 2016 DxE Tech Working Group <tech@directactioneverywhere.com>
This work is free. You can redistribute it and/or modify it under the
terms of the Do What The Fuck You Want To Public License, Version 2,
as published by Sam Hocevar. See the COPYING file for more details.
