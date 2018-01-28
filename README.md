# urlscan-weechat

This is a simple [weechat](https://weechat.org/) plugin that allows you
to pipe buffers through [urlscan](https://github.com/firecat53/urlscan).
This gives you an interactive list of URLs to open, which is especially
helpful if there are multiple URLs in the buffer making
[urlgrab](https://weechat.org/scripts/source/urlgrab.py.html/) hard to
use.

## Installation

Copy the script to `~/.weechat/python/autoload`

```sh
mkdir -p ~/.weechat/python/autoload
wget https://raw.githubusercontent.com/alx741/urlscan-weechat/master/urlscan.py ~/.weechat/python/autoload
```

This is a fork from the *urlview* [version of the
plugin](https://github.com/keith/urlview-weechat) which is a python rewrite of
[this ruby plugin](https://weechat.org/files/scripts/unofficial/urlview.rb)
