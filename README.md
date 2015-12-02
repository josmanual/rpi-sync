# Raspberry Pi Intenet Sync

Meet your public IP to access your Raspberry Pi (in LAN) from Internet.

## Setup

1. Configure a static IP for the Raspberry in your LAN. In order to use port forwarding in the router.
2. Get a public host. Where the Raspberry sends the information.
3. In the public host, create a DB and a Table to store the data.
4. In the public web site, create a PHP site where get the information from the Raspberry and obtain the IP.
5. Install the scrypt in the Pi to connect to your public site.
