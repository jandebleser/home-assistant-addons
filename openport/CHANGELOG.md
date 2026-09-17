# Changelog

## 1.0.1

- Connect to Home Assistant over 127.0.0.1 instead of ::1, so only
  `127.0.0.1` needs to be in `http.trusted_proxies`.

## 1.0.0

- Initial release: openport http-forward tunnel to the Home Assistant
  frontend, with WebSocket support.
- Openport client v2.2.3.
