#### Xampp Users

1. Go to xampp\phpMyAdmin\
2. Open config.inc.php
3. Search for $cfg['ExecTimeLimit'] = 300;
4. Change to 0 for unlimited or put a larger value
5. If not found, look in xampp\phpMyAdmin\libraries for config.default.php
6. Search for $cfg['ExecTimeLimit'] = 300;
7. Change to 0 for unlimited or put a larger value
7. Save the file and restart the server

Note: It might be possible to add $cfg['ExecTimeLimit'] = 0; to config.inc.php file if it doesn't exist.