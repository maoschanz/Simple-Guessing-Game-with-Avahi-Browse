# Simple-Guessing-Game-with-Avahi-Browse

Simple number guessing game which advertises its instance using Avahi / Zeroconf.

## Dependencies

```
sudo apt install libavahi-compat-libdnssd-dev
```

See [this file](/usr/include/dns_sd.h) for documentation, or maybe
[this one](/usr/include/avahi-compat-libdns_sd/dns_sd.h)? Look similar.

## Compilation

```
gcc avaserv_final.c -ldns_sd -lm -o avaserv
```

## TODO

```
*** WARNING *** The program 'avaserv' uses the Apple Bonjour compatibility layer of Avahi.
*** WARNING *** Please fix your application to use the native API of Avahi!
*** WARNING *** For more information see <http://0pointer.de/blog/projects/avahi-compat.html>
```

