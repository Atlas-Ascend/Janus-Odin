# 08 — CrownGrid and Event Routing

JANUS–ODIN requests capabilities through Packet OS/CrownGrid rather than binding directly to repo or host names.

Consumes: directive.requested, packet.blocked, proof.rejected, organ.degraded, risk.detected, priority.conflict.
Emits: directive.authorized, directive.denied, packet.authorized, priority.changed, escalation.created, execution.paused/resumed.