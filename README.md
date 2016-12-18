sic - simple irc client
=======================
sic is an extremly fast, small and simple irc client.  It reads commands from
standard input and prints all server output to standard output. It multiplexes
also all channel traffic into one output, that you don't have to switch
different channel buffers, that's actually a feature.


Installation
------------
Edit `config.mk  to match your local setup. sic is installed into
_/usr/local_ by default.

Afterwards enter the following command to build and install sic 
(if necessary as root):

    $ make clean install


Running sic
-----------
Simply invoke the `sic` command with the required arguments.

The following arguments are accepted:

- k: a `PASS`word for the remote server
- h: the host to connect to
- p: the port to use
- n: the `NICK` to use
- v: version information
- H: the help message
