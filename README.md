# proxy-list

Proxies are checked on my VPS every 30 minutes using [multics76/proxy-scraper-checker](https://github.com/multics76/proxy-scraper-checker).

## Folders description

- `proxies` - proxies with any anonymity level.
- `proxies_anonymous` - anonymous proxies.
- `proxies_geolocation` - same as `proxies`, but includes exit-node's geolocation.
- `proxies_geolocation_anonymous` - same as `proxies_anonymous`, but includes exit-node's geolocation.

Geolocation format is `ip:port|Country|Region|City`.

## License

[MIT](LICENSE)
