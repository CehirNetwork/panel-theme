
## Steps to install for staff:
1. Download or make the file build.sh in the /var/www/pterodactyl dir
2. Make sure the build.sh has permissions to run `chmod +x /var/www/pterodactyl/build.sh`
3. Run the install script: if in the /var/www/pterodactyl dir run: `./build.sh`
4. Run the install script pt2, if not in the directory run `/var/www/pterodactyl/build.sh`
5. Modify the .env file `nano /var/www/pterodactyl/.env` change pterodactyltheme to `argon`
6. Run these commands after you saved the file: `php artisan theme:refresh-cache` `php artisan view:clear`
7. Refresh the browser `CTRL+F5` Success.

## Themes Ready for you to use:
`argon`

https://pterodactyl.io/panel/configuration.html
