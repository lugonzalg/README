## ssh automatic connection

First create a ssh key

    ssh-keygen

Send the key using ssh-copy-id

  ssh-copy-id -i <path_to_key.pub> host@ip
