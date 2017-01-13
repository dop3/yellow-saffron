# yellow-saffron

## Todo 1:
1. install Virtualbox
2. install Vagrant
3. via vagrant -> create a virtual machine with the last ubuntu server stable version
4. in the newly created VM, install Lamp stack
   1. Apache2
   2. PHP
   3. MySql (or MariaDB)
5. configure HOST (your pc) and GUEST (the VM):
   1. configure hosts in HOST
   2. configure shared folders (HOST <-> GUEST)
   3. in GUEST configure a vhost
6. create a php file with this code:

`<?php phpinfo(); ?>`

7. access this newly created file via browser from HOST

#### That's it!
  
