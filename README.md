# AdminerCustomizeThemeBasedOnServer

The plugin AdminerCustomizeThemeBasedOnServer enables the customization of the
active theme based on the active server selected.
- see Adminer - Database management in a single PHP file https://www.adminer.org/

It tries to add a SERVER specific CSS file using the following convention
- same directory as adminer.css
- name it server-[SERVER]-adminer.css
- add any additional CSS styles, you want to apply to the adminer.css
  or the default.css

See the example
- adminer/plugin.php to add the plugin AdminerCustomizeThemeBasedOnServer
- adminer/server-MY.LOCAL-adminer.css
- adminer/server-MY.LOCAL-ICON.png
- plugins/customize-theme-by-server.php
- run the adminer/index.php and set server to MY.LOCAL
