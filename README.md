# 534rch
a shell script to search on internet from terminal.

[![534rch](https://serving.photos.photobox.com/446469324a0e7e782c70c37e3fdbe2e8a0d8dce6125f86c1e6c5b8c0071ff50265a7888d.jpg)](https://youtu.be/QcC9RStc0TE "534rch shell script")

About
------

This script was a part of my school project (init) on 42 Cursus.(https://1337.ma/)

Installation
------------

- Clone the  the entire repository:
```sh
git clone https://github.com/do02/534rch
```

- and install this script using alias command:
```sh
alias se='sh ~/Desktop/534rch/se'
```

Usage
-----

```sh
usage: se [-h] [WEBSITE] [KEYWORD "KEYWORD ..."]
```

**Options:**

```sh
534RCH: Search from terminal.

positional arguments:
	WEBSITE				website to search on
	KEYWORD				search keyword

optional arguments:
	-h, --help			show this help message and exit

WEBSITE:
	google, go				https://www.google.com
	youtube, yt				https://www.youtube.com
	stackoverflow, stack			https://stackoverflow.com
	duckduckgo, duck			https://duckduckgo.com
	intra, 42				https://profile.intra.42.fr
```

Example
-------

```sh
$> se

888888888   .d8888b.      d8888  8888888b.   .d8888b.  888    888
888        d88P  Y88b    d8P888  888   Y88b d88P  Y88b 888    888
888             .d88P   d8P 888  888    888 888    888 888    888
8888888b.      8888"   d8P  888  888   d88P 888        8888888888
     "Y88b      "Y8b. d88   888  8888888P"  888        888    888
       888 888    888 8888888888 888 T88b   888    888 888    888
Y88b  d88P Y88b  d88P       888  888  T88b  Y88b  d88P 888    888
 "Y8888P"   "Y8888P"        888  888   T88b  "Y8888P"  888    888
                                                         by: do02

 ~~~*{choose where you want to search}*~~~

 1) StackOverflow
 2) Youtube
 3) Google
 4) DuckDuckGo
 5) Intra 42

entre number:
```

```sh
$> se yt "live overflow"
 Searching on Youtube for live overflow
```

```sh
$> se 42 adouz
 Searching on Intra.42 for adouz
```
