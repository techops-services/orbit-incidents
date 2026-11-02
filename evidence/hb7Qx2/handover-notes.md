# Shift handover, 2026-11-01 evening

- 16:37 UTC: HeartbeatStale on worker-1 and worker-3 (mainnet).
  Same pattern: events arrive, publishes time out after 20s, many queue reconnects.
- Captured logs, restarted each worker once. Both cleared by 17:05.
- Posted in #orbit-workers. They are looking into the message queue. No root cause yet.
