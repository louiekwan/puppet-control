Puppet infrastructure 

To try it out, clone the repo and then run:

    scripts/start_vagrant.sh

from within the repo directory. (If you don't have Vagrant installed, go to the [Vagrant Downloads page](https://www.vagrantup.com/downloads.html)).

Alternatively, to bootstrap a server, all you will need is the IP address or DNS name of the target server. Run the following command from the Puppet repo, replacing `TARGET_SERVER` with the address or name of the server, and `HOSTNAME` with the hostname that you want to set (for example `demo`):

    scripts/puppify TARGET_SERVER HOSTNAME

