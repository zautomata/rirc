#rirc

A minimalistic irc client written in C.

While still under development, it currently supports
many features which you would expect from a basic
irc client.

##Building:
make

##Usage:
```
  rirc [-c server [OPTIONS]]

Help:
  -h, --help             Print this message

Options:
  -c, --connect=SERVER   Connect to SERVER
  -p, --port=PORT        Connect using PORT
  -j, --join=CHANNELS    Comma separated list of channels to join
  -n, --nicks=NICKS      Comma/space separated list of nicks to use
  -v, --version          Print rirc version and exit

Examples:
  rirc -c server.tld -j '#chan' -n nick
  rirc -c server.tld -p 1234 -j '#chan1,#chan2' -n 'nick, nick_, nick__'
```

##More info
[rcr.io/rirc](http://rcr.io/rirc)

##Screenshots:
![image](https://raw.github.com/robbinsr/rirc/master/rirc.png?raw=true)
