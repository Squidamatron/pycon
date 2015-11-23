# pycon
A simple argument based program to manage TF2 servers.
## Usage

```
usage: pycon [-h] -a ADDR [-p PORT] [-e CFG] [-l LEVEL] [-m LIST] [-k ID] [-s]
             [--restart]

optional arguments:
  -h, --help            show this help message and exit
  -a ADDR, --addr ADDR  Sets the address to connect to. This option is
                        mandatory and must be set.
  -p PORT, --port PORT  Sets the port to connect if a port other than 27015 is
                        used. The default setting is 27015.
  -e CFG, --exec CFG    Execs a config file on the server.
  -l LEVEL, --level LEVEL
                        Changes the level on the server. Full map name
                        required.
  -m LIST, --maplist LIST
                        Lists available maps on the server.
  -k ID, --kick ID      Kick a user off the server using their from Status
                        (-s)
  -s, --status          Prints the output of the status command. This will
                        happen with no other server arguments.
  --restart             Restarts the server.
```
## Requirements
* Python 2.7
* [python-valve](https://github.com/Holiverh/python-valve)
