# Stuart's Home Assistant Add-ons

Add-ons for Home Assistant, allowing you to extend the functionality around your home automation setup.

## Installation

Adding this add-ons repository to your Home Assistant instance is pretty straightforward. Follow [the official instructions][third-party-addons] on the website of Home Assistant, and use the following URL:

```txt
https://github.com/stuartparmenter/homeassistant-addons
```

## Add-ons provided by this repository

### ➕ [Media Proxy][media-proxy-addon]

![Supports aarch64 Architecture][media-proxy-aarch64-shield]
![Supports amd64 Architecture][media-proxy-amd64-shield]

_WebSocket-controlled media proxy that outputs DDP (UDP)_

Stream videos, GIFs, still images, and YouTube content to tiny LED/LCD displays (e.g., ESPHome devices using DDP) with smart resizing, optional color-range expansion, and packet pacing.

[:books: Media Proxy add-on documentation][media-proxy-addon-doc]

## Support

For issues with specific add-ons, please file them in the individual add-on repositories:
- [Media Proxy Issues](https://github.com/stuartparmenter/media-proxy-addon/issues)

## License

MIT License - see [LICENSE](LICENSE) file for details.

[media-proxy-addon]: https://github.com/stuartparmenter/media-proxy-addon
[media-proxy-addon-doc]: https://github.com/stuartparmenter/media-proxy-addon/blob/main/README.md
[media-proxy-aarch64-shield]: https://img.shields.io/badge/aarch64-yes-green.svg
[media-proxy-amd64-shield]: https://img.shields.io/badge/amd64-yes-green.svg
[third-party-addons]: https://www.home-assistant.io/common-tasks/os/#installing-third-party-add-ons