# cssh
A tmux based cssh like tool for Bash

useage: cssh server1 server2 server3 ...

set your username in the script or it will assume its the same as your local username
It will auto add your ssh key (~/.ssh/id_rsa) 
Bound Keys are: 
CTL-A for for prefix key
CTL-A + a bind keys to all panes (default)
CTL-A + b unbind keys from all but active pane
CTL-A + <arrow key> change active pane (standard)
All other Tmux commands are standard (remembering the prefix key is CTL-A)
