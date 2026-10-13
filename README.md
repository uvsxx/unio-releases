# unio releases

Public downloads of unio, the team task tracker. Built and published by the
release workflow of the (private) source repository; nothing here is edited by hand.

Every release carries `manifest.json` with the SHA-256 of each binary and `manifest.json.sig`, an
ECDSA P-256 signature over it. unio verifies that signature against the keys built into it before
it installs an update, so a copy of these files on any other host is just as good.

Install:

    # Windows (PowerShell)
    irm https://github.com/uvsxx/unio-releases/releases/latest/download/install.ps1 | iex

    # Linux, macOS
    curl -fsSL https://github.com/uvsxx/unio-releases/releases/latest/download/install.sh | sh
