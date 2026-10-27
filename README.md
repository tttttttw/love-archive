# Our Archive — static prototype

A phone-first, contemporary literary archive prototype. The archive content is encrypted in the browser using PBKDF2-HMAC-SHA256 and AES-256-GCM. The HTML stores ciphertext, not plaintext archive content.

## Passphrase
The archive is locked with a passphrase that is not stored in this repository. A short passphrase is easier to guess offline, so use a longer one if the content is sensitive.

## GitHub Pages
In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. After publishing, the site URL should be `https://tttttttw.github.io/love-archive/`.

GitHub Pages serves public files. Privacy depends on strong client-side encryption, not on the repository being public. Anyone who learns the passphrase can decrypt the content, and a visitor can copy content after unlocking.
