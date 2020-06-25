Installation Guide - Spark Theme

 - Drag and Drop files into /var/www/pterodactyl.
 - Allow overwriting if asked.
 - Once done uploading, refresh your Pterodactyl Panel.
 - Now head over to /var/www/pterodactyl and edit the file named ".env". (If you cannot see this file, enable "show hidden files".)
 - Edit the line marked with "APP_THEME=pterodactyl" to "APP_THEME=spark".
 - SSH into your Panel host machine.
  - Copy and Paste the following command:
 
  **cd /var/www/pterodactyl && php artisan view:clear && php artisan theme:refresh-cache && php artisan queue:flush**
  
 - Refresh your Pterodactyl Panel and enjoy your new theme!
