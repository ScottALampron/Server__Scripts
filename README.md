# bash

"clean_init.sh" is set to wipe all the actions created in the "server_init.sh" script from the current defaults.

server_init.sh is intended for initial server boot. creates ssh keys, updates the app list, and sends your IP to your location of choice. 
also sends and modifies the public ssh keys, and authorized_keys to make ssh set-up even easier.

Look threw the variables in the header of server_init.sh before executing. Change the username, and appropriate values, such as your server/client IP address to send the keys to, also the kind of keys you would like, and all the other options.

There are a lot of other features I would like to incorporate into this as well.
