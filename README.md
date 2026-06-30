# KinkySync

KinkySync is an upcoming Dalamud plugin for consent-based, two-person scene
synchronization.

The project is planned to include:

- A standalone Dalamud plugin that keeps contacts, trust, pairing, and consent
  decisions local to each player.
- A lightweight Cloudflare Worker and Durable Object relay for real-time scene
  messages between two connected clients.
- Scene pack manifests served from Cloudflare R2.
- Clear separation from PMPSHARE and other plugin projects.

The relay does not transfer character assets or scene files. Development work
currently lives on the `testing` branch while the architecture and plugin MVP
are being established.
