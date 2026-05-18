# rust-http

Building an HTTP server from scratch in Rust. No frameworks. Standard library only until Phase 5.

## Phases

- [ ] Phase 1 — Hello TCP
- [ ] Phase 2 — Parse the Request
- [ ] Phase 3 — Route and Respond
- [ ] Phase 4 — Serve Files
- [ ] Phase 5 — Concurrency
- [ ] Phase 6 — Thread Pool

## Run

```bash
cargo run
```

Then in another terminal:

```bash
curl -v http://127.0.0.1:8080
```

## Rules

- No Actix, no Axum, no Tokio until Phase 5
- Standard library only
- Read the Rust book when stuck, not before
