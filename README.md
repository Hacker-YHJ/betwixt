# Betwixt

This tool will help you analyze web traffic outside the browser using familiar Chrome DevTools interface.

![Betwixt in action](http://i.imgur.com/ccgmL2C.gif)

**This project is in an early stage of development, things may break, values may not be accurate. All contributors are very welcome. See [CONTRIBUTING.md](CONTRIBUTING.md) fore more details.**

## Installing

Download the [latest release](https://github.com/kdzwinel/betwixt/releases/latest) for your operating system, [build your own bundle](docs/building.md) or [run Betwixt from the source code](docs/building.md).

## Setting up

In order to capture traffic, you'll have to direct it to the proxy created by Betwixt in the background (`http://localhost:8008`).

If you wish to analyze traffic system wide:
- on OS X - `System Preferences → Network → Advanced → Proxies → Web Proxy (HTTP)`
- on Ubuntu - `All Settings → Network → Network Proxy`
- on Windows - `PC Settings → Network → Proxy`

![Setting up proxy on OS X](http://i.imgur.com/QL3cE6L.png)

If you want to capture traffic coming from a single terminal (e.g. wget, npm) use `export http_proxy=http://localhost:8008`.

#### License [MIT](LICENSE.md)
