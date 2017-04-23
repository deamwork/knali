# knali

## Overview

A native [nali](http://www.surfchen.org/nali) replacement.

**All contribute are come from [kosaka](https://t.me/kosaka)**

Original nali uses Perl and a helper program to capture the text output using regex and append geolocation data directly. It has several problems like text overlap, redundant output, etc.

The knali prints the geolocation data on screen by modifying source code of the tool. It provides the native experience and better performance.

knali proudly uses the best IP database from [IPIP.net Official Site](https://www.ipip.net/).

## Usage

Compile code, and put IP database file `17monipdb.dat` at `/usr/local/share`.

macOS users can use binaries in build/macOS directory.

IP database can be downloaded at [here](https://www.ipip.net/download.html).

## License

The code uses the same license as what it is based on.

* ping, traceroute: based on [GNU inetutils](https://www.gnu.org/s/inetutils), GPLv3
* mtr, mtr-packet: based on [mtr](https://github.com/traviscross/mtr), GPLv2
* dig, host, nslookup: based on [BIND9](https://www.isc.org/downloads/bind/), MPLv2

