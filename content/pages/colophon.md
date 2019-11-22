+++
title = "baemazhen :: colophon"
path = "colophon"
template = "spage.html"
+++

## Technology

This website is built using [Zola](https://www.getzola.org/), a static site generator.

It is currently hosted on an [Ubuntu Linux](https://ubuntu.com/server) VPS instance and served by [Nginx](https://nginx.org/).

SSL certificates are provided by [Let's Encrypt](https://letsencrypt.org/).

This website **DOES NOT** contain:

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

This is deliberate and by design... **remember the old ways**.

### Deployment

Deployment simply consists of running `zola build` locally and then using `scp` (secure copy) to copy the generated output to the server.

No need for CI, build pipelines, git hooks, etc. just to deploy a static website... **remember the old ways**.

## License and Source

The content for this site is [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). The code for this site is [MIT](https://opensource.org/licenses/MIT). 

Source code and site content is available on GitHub at [baemazhen/baemazhen](https://github.com/baemazhen/baemazhen)