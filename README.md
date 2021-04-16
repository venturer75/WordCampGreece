# WordCampGreece

Create a fresh install of WP

Install 00_LATEST-ALL_IN_ONE_7.17 plugin and update

Import wp-greece.wpress file

Update any other plugins

server.php in root will set $SITE = esc_url(site_url()).'/' so that all the FETCH APIs will use your current site as the root URL.

OPTIONAL: run 01_tblTest.sql in root in phpMyAdmin for your WP database.

This will enable us to query a custom MySql Table but is not necessary as there are other datasets we also use.

## There is YouTube video showing all this at: https://www.youtube.com/watch?v=F0pTat9CQtg&list=PLsszRSbzjyvka3TZUBr4Kfs10w9yry41c&index=1
