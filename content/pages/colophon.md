+++
title = "baemazhen :: colophon"
path = "colophon"
template = "spage.html"
+++

## Access

- WWW: [baemazhen.com](https://www.baemazhen.com)
- Tor: [57rwj2hdhdsvw6qunvzbiaqbkx2g6y5vysfwn7liihamnku7dlamy4yd.onion](http://57rwj2hdhdsvw6qunvzbiaqbkx2g6y5vysfwn7liihamnku7dlamy4yd.onion)

## Technology

This website is built using [Zola](https://www.getzola.org/), a static site generator.

It is currently hosted on an [Ubuntu Linux](https://ubuntu.com/server) VPS instance and served by [Nginx](https://nginx.org/).

SSL certificates are provided by [Let's Encrypt](https://letsencrypt.org/).

This website deliberately **DOES NOT** contain:

- JavaScript
- cookies
- bloated CSS framework
- remotely loaded assets or fonts
- comments
- emojis
- embedded social media
- trackers
- advertisements
- more cowbell

### Deployment

Deployment simply consists of running `zola build` locally and then using `scp` (secure copy) to copy the generated output to the server.

## License and Source

The content for this site is [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). The code for this site is [MIT](https://opensource.org/licenses/MIT). 

Source code and site content is available on GitHub at [baemazhen/baemazhen](https://github.com/baemazhen/baemazhen)