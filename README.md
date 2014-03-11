storymap5
=========

Wie gut kennen Sie die Schweiz von früher (Swissguessr) ?

1/ Install 

   cd /var/www/vhosts/web-storymap5/private 

   git clone git@github.com:geoadmin/web-storymap5.git storymap

   sudo apache2ctl graceful

2/ Deploy

   cd /var/www/vhosts/web-storymap5/private/storymap

   sudo -u deploy deploy -r deploy/deploy.cfg int   # or prod
