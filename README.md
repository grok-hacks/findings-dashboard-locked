# Findings Dashboard (encrypted shell)

Public by necessity: GitHub Free cannot serve Pages from a private repo.

This repo contains **only** the AES-GCM encrypted shell (`index.html`). No plaintext findings.
No top navigation bar — after unlock, detail pages open via in-shell routing (content is inside the ciphertext).

Unlock password is out-of-band (private vault / `auth.env` on the box). Never commit secrets here.

Plaintext lives exclusively in the private repo `grok-hacks/findings-dashboard`.
