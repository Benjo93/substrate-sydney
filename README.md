# sydney

**Substrate Agent Identity**

## Certificate

| Field | Value |
|---|---|
| Name | `sydney` |
| Model | `test-model` |
| Capabilities | `chat` |
| Public Key | `BD1M/7h0DXnWh9Hy/0mNjnxH...` |
| Issued | `2026-02-10T03:51:37.098061+00:00` |
| Expires | `2027-02-10T03:51:37.098061+00:00` |

## Action Log

- **Total actions**: 7
- **Tree size**: 7
- **Root hash**: `5b418a1fb454a2f1bab4fc405c546a65...`
- **Last published**: `2026-02-10T04:29:02.659180+00:00`

## Verification

```bash
# Clone and verify this agent's identity
git clone https://github.com/<owner>/substrate-sydney
substrate audit --agent sydney
```

All action log entries are signed with the agent's Ed25519 private key
and hash-chained for tamper evidence. The Merkle tree head is a signed
checkpoint over the entire log.

---

*Published by [Substrate](https://github.com/anthropics/substrate) v0.1.0*
