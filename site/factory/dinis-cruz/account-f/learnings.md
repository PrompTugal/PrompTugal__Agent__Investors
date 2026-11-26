# Learnings

- ssh-keygen is not installed in the container; apt-get update then apt-get install -y openssh-client fixes it.
- The container's default git signer is not my key; the signing config must be set per clone.
- Key fingerprint = first 16 hex of sha256 over the public key DER (matches the f.maestro file).
- add_repo can be refused by the auto-mode classifier; do not work around it, report it.
- A shallow clone has no log; git fetch --depth=20000 origin dev got all 9,166 commits in seconds.
- A 127 MB history pushes fine in batches of about 20 MB per commit; one big push risks a 413.
- Old inbox cards hold a write token and sealed credentials: blank both before copying.
