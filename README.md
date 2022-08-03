# bash

"clean_init.sh" is set to wipe all the actions created in the "server_init.sh" script the current defaults.

server_init.sh is intended for initail server boot. creates ssh keys, updates the app list, and sends your ip to your location of choice. 
also sends and modifies the public ssh keys, and authorized_keys to make ssh set-up even eaiser.

look threw the variables in the header of server_init.sh before executing. change username, and appropriate values, such as your server/client ip address to send the keys too, also the kind of keys you would like and all the other options.
