# annjenita-covers

Public host for Instagram Reel cover images.

Meta's content-publishing API fetches `cover_url` server-side over HTTP, so a cover
must sit at a public URL for the few seconds a publish takes. These images are
published to Instagram anyway, so nothing here is private.

Covers are pushed by `cutform/publish/cover-host.mjs` and referenced by their
`raw.githubusercontent.com` URL.
