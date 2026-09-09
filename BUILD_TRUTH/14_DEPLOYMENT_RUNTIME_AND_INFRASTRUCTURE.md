# 14 — Deployment, Runtime, and Infrastructure

JANUS–ODIN may run as a durable control-plane service with operator UI bindings and resident worker integration. Production requires authenticated directive ingress, durable decision ledger, policy store, event integration, health endpoint, and backup/recovery.

Local/offline mode may exist but must reconcile back to canonical state.