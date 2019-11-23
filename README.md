# baemazhen.com

Static website for [baemazhen.com](https://baemazhen.com) built with [Zola](https://github.com/getzola/zola).

It uses a modified version of the [after-dark](https://github.com/getzola/after-dark) theme.

## Development

You will need Zola installed: [Instructions](https://www.getzola.org/documentation/getting-started/installation/)

### Running It

Run the site locally while making changes:
```bash
zola serve
```

Site will be accessible at http://127.0.0.1:1111

### Building and Deploy WWW site

Build the WWW site (outputs generated site to `public/`):
```bash
zola build
```

Deploy the changes
```bash
scp -r public/* user@example.com:/home/user/www/
```

### Building and Deploy Tor site

Build the Tor site (outputs generated site to `onion/`)
```bash
zola build --base-url http://57rwj2hdhdsvw6qunvzbiaqbkx2g6y5vysfwn7liihamnku7dlamy4yd.onion --output-dir onion
```

Deploy the changes
```bash
scp -r onion/* user@example.com:/home/user/onion/
```

## License

The content (pages and articles) for this site is [CC-BY-4.0](https://creativecommons.org/licenses/by/4.0/). 

The code for this site is [MIT](LICENSE.md). 