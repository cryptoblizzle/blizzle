# Apache Layer

This directory documents the Apache-facing layer used Blizzle.

The live Blizzle deployment uses Apache as the public web layer in front of the application experience. Apache is responsible for serving public static assets, routing browser traffic, and supporting the production web entry points.

## Documented Structure

- `conf/` — Apache site configuration references
- `ssl/` — SSL/TLS configuration references
- `proxy/` — reverse-proxy routing notes for backend services

Production Apache configuration, certificates, private keys, server paths, and sensitive deployment details are intentionally excluded from this public repository.
