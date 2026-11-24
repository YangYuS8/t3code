# Product analytics in this fork

The application has no product event sender or account attribution pipeline. Authentication may read the active provider credential for sign-in. WebSocket tickets and DPoP proofs authenticate the connection. Local usage records serve the usage view. These paths must stay independent of diagnostics.

See [privacy and user-configured diagnostics](../user/telemetry.md).
