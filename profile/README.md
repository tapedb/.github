# TapeDB

**Typed models. Live data. Your Cloudflare account.**

TapeDB is a TypeScript database library for Cloudflare. Define your models once,
query with types, subscribe to live updates, and queue single-row writes while
offline. Each workspace gets its own SQLite database inside a Durable Object,
with transaction logs and snapshots stored in R2.

### Build with your data

- **Typed models and relations** — one schema drives your client types, engine registry, and migrations.
- **Live queries** — subscribe to the queries you already use and receive row-level updates.
- **Offline writes** — optimistic single-row updates with a persistent outbox and bounded retry deduplication.
- **Your infrastructure** — Workers, Durable Objects, and R2 in your own Cloudflare account, with your application's identity provider.

### In development

TapeDB is pre-1.0. The library repository remains private while release validation
and documentation are completed. Public package availability has not been
announced.
