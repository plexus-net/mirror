# Plexus network mirror

`docs.cbor` — the current Plexus network documents (directory root, shards,
relay list), published automatically.

- Every document inside is signed by a quorum of Plexus network monitors.
  Clients verify the signatures themselves, so this mirror does not need to be
  trusted: a modified or outdated file is simply rejected.
- Clients use this mirror only as a fallback, when the peer-to-peer network is
  unreachable.
- The file is updated by a bot; history is not kept (one commit, force-pushed).
  Please do not send pull requests here.

https://get-plexus.com
