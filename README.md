## OpenDock
OpenDock is an open source frontend for the [SpaceDock-Backend](https://github.com/KSP-SpaceDock/SpaceDock-Backend) software, an API backend for hosting game modifications.
This a project to develop a frontend that is capable of using the data provided by the SpaceDock-Backend API, to display a fully useable mod site. When it is finished, it has the potential to become the official frontend
used by [spacedock.info](https://spacedock.info).

### SDB Plugins
OpenDock requires the installation of plugins in the SDB instance it uses. These plugins are located in [SpaceDock-Extras](https://github.com/KSP-SpaceDock/SpaceDock-Extras), namely

* adapter
* ckan
* media
* search
* transformers

The `plugins.txt` file that gets used should look like this

```
github.com/KSP-SpaceDock/SpaceDock-Extras/plugins/adapter
github.com/KSP-SpaceDock/SpaceDock-Extras/plugins/ckan
github.com/KSP-SpaceDock/SpaceDock-Extras/plugins/media
github.com/KSP-SpaceDock/SpaceDock-Extras/plugins/search
github.com/KSP-SpaceDock/SpaceDock-Extras/plugins/transformers
```

### Authors
The list of authors can be found in the [THANKS file](THANKS).

### License
This application is licensed under the MIT License. You are free to remix, adapt and redistribute it, however, please credit the original authors

OpenDock uses the slim, jQuery and vue.js frameworks to do its work.

It uses the following jQuery Plugins:
* http://www.jqueryscript.net/loading/Small-Loading-Modal-Overlay-Plugin-With-jQuery-loadingBlock.html
* http://stefangabos.ro/jquery/zebra-dialog/

The icon was created by Freepik © Flaticon