# Support

A shared support page for the open-source projects of **Grigory Olshansky**.

**[Open the support page →](https://hawkab.github.io/support/)**

The page offers a TON wallet link, QR code and copy buttons. It works on desktop and mobile browsers, follows the device's light or dark theme and has no tracking or external dependencies. Payment amounts and confirmation stay in the user's wallet.

Reuse `https://hawkab.github.io/support/` in a project README, an AppStream donation URL or GitHub's `.github/FUNDING.yml`:

```yaml
custom:
  - https://hawkab.github.io/support/
```

GitHub Pages publishes the static files from the root of `main`. To preview locally, run `python3 -m http.server 8000` and open `http://localhost:8000/`.

When changing the payment link, update the recipient and jetton in `index.html`, and regenerate `support-qr.png` from the complete `ton://transfer/…?jetton=…` URI. Keep both representations identical.

Copyright © 2026 Grigory Olshansky. Licensed under [GPL-3.0-or-later](LICENSE).
