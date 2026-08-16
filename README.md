# SeriousSportSync

Personal deployment wrapper for SeriousSportSync.

The upstream project is a self-hosted sports calendar and stream orchestrator for Nuvio and Stremio-compatible clients. It supports UFC, ONE Championship, WWE, AEW, Formula 1, MotoGP, boxing and custom promotions. Playback is optional and uses user-configured services; the application itself hosts no media. See the upstream project for the full configuration and responsible-use details.

## Deploy on Render

1. Create a new Blueprint in Render from this repository.
2. Select `render.yaml`.
3. Deploy.
4. Open the generated service URL.
5. Complete the initial admin setup.
6. Copy the private install URL from the SeriousSportSync Account page and add it to Nuvio/Stremio.

The Dockerfile tracks the upstream published container image, so the repository stays small while using the upstream release.

Upstream: https://github.com/Monkfish1337/Serioussportsync
