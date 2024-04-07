# routercfg

routercfg is a Python script to configure a Zyxel NBG6615 with terminal
commands.

Make a file containing only the login password and edit the fields in
routercfg.ini before using. For example:

    echo my-router-password > /path/to/password

In routercfg.ini, write:

    [router]
    address = http://router-address-here
    password_file = /path/to/password

