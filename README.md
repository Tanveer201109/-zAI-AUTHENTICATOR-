# [zAi] AUTHENTICATOR
**[zAi] The Faith Standard** — OWN GOD GIFTED OWN PLATFORM

A real TOTP (RFC 6238) authenticator in one self-contained `index.html`.
No build step, no server, no external images, no API keys.

- SHA1 / SHA256 / SHA512, 6–8 digits, custom period
- Add by Base32 secret, `otpauth://` link, or QR image (Chrome / Android)
- Live countdown ring, tap to copy
- Optional AES-256-GCM vault passphrase (PBKDF2, 250k iterations)
- JSON backup export / import
- Secrets never leave the device

## Run
Open `index.html` in Chrome, or serve it: `python3 -m http.server 8080`

## Deploy (free)
GitHub Pages is deployed by `.github/workflows/pages.yml` on every push to `main`.
Enable it once: Settings → Pages → Source: **GitHub Actions**.
