# Our Archive — static prototype

A phone-first, contemporary literary archive prototype. The archive content is encrypted in the browser using PBKDF2-HMAC-SHA256 and AES-256-GCM. The HTML stores ciphertext, not plaintext archive content.

## Important before using real private content
The current demo passphrase is `o728!`, which is short and weak. Do not use it for private writing. Replace it with a long, unique passphrase and re-encrypt your final content before sharing the site.

## GitHub Pages
In the repository, open **Settings → Pages**, choose **Deploy from a branch**, select `main` and `/(root)`, then save. After publishing, the site URL should be `https://tttttttw.github.io/love-archive/`.

GitHub Pages serves public files. Privacy depends on strong client-side encryption, not on the repository being public. Anyone who learns the passphrase can decrypt the content, and a visitor can copy content after unlocking.
