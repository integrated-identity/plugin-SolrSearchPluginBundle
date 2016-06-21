SolrSearchPluginBundle
======================

This plugin adds functionality to Newscoop for using Solr as a search engine.

Installation
-------------
Installation is a quick process:


1. How to install this plugin?
2. That's all!

### Step 1: How to install this plugin?
Run the command:
``` bash
$ php application/console plugins:install "newscoop/solr-search-plugin-bundle"
$ php application/console assets:install public/
```
Plugin will be installed to your project's `newscoop/plugins/Newscoop` directory.

### Step 2: That's all!
Go to Newscoop Admin panel and then open `Plugins` tab. The Plugin will show up there. You can now use the plugin.


**Note:**

To update this plugin run the command:
``` bash
$ php application/console plugins:update "newscoop/solr-search-plugin-bundle"
$ php application/console assets:install public/
```

To remove this plugin run the command:
``` bash
$ php application/console plugins:remove "newscoop/solr-search-plugin-bundle"
```

Documentation
-------------

Documentation can be found [here](https://wiki.sourcefabric.org/display/CS/Solr+for+frontend+searching).

License
-------

This bundle is under the GNU General Public License v3. See the complete license in the bundle:

    LICENSE

About
-------
This Bundle is a [Sourcefabric z.ú.](https://github.com/sourcefabric) initiative.
