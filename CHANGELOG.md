# Changelog

## [Unreleased]

## [0.1.0] - 2026-08-14

First public release: a terminal client that tunnels a remote database to localhost over Cloudflare Access (TCP), with no VPN or open ports.

- Two builds: embedded (cloudflared `2025.4.0` built in) and external (your own cloudflared, set by `cloudflared_path` in `config.yml`).
- Panel dashboard: connection health, session info (port, PID, target) and live log in one view.
- Health checks for the host and cloudflared, with one-key retry (`P` / `E`).
- Cloudflare Access login on first connect, cached after.
- Single portable `.exe`, no install.
