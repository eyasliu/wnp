# WNP
windows client nginx + php auto install and manager

# Install

1. clone this repo
2. set work dir and install it

```
git clone https://github.com/eyasliu/wnp.git
cd wnp
wnp install
```

## about webroot

the default webroot is `D:\wnpserver\www`

you can change file `./wnp` line 2 before install to define you webroot

# Usage

1. `wnp {start|stop|restart}` to star or stop or restart nginx + php server
2. `wnp nginx xxxx` manage nginx

```
> wnp help
wnp {start|stop|restart}

> wnp nginx -h
nginx version: nginx/1.11.3
Usage: nginx [-?hvVtTq] [-s signal] [-c filename] [-p prefix] [-g directives]

Options:
  -?,-h         : this help
  -v            : show version and exit
  -V            : show version and configure options then exit
  -t            : test configuration and exit
  -T            : test configuration, dump it and exit
  -q            : suppress non-error messages during configuration testing
  -s signal     : send signal to a master process: stop, quit, reopen, reload
  -p prefix     : set prefix path (default: NONE)
  -c filename   : set configuration file (default: conf/nginx.conf)
  -g directives : set global directives out of configuration file

> wnp nginx -v
nginx version: nginx/1.11.3
```
