## Synchronous Image Resizer PHP


Simply Host the `index.php` script on a server _e.g. http://img.example.com_ along side the `.htaccess` script, in the same directory.

To Resize an image simply load `http://img.example.com/[W]/[H]/i/www.site.com/img/big_picture.jpg`

Where `[W]` is the Width, `[H]` is the Height, and `/i/` is just a delimiter. So a working example will be `http://img.example.com/64/64/i/www.site.com/img/big_picture.jpg`

_If you would like to host it in a custom directory edit the RewriteBase on line 6 in `.htacces` to relect the location of the current working directory. For Example if its hosted in example.com/img/server/, your RewriteBase should be `RewriteBase /img/server/`_


