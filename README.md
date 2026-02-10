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

- **Total actions**: 10
- **Tree size**: 10
- **Root hash**: `633b6bbf9e56bd5656ded5b2e7cec3d1...`
- **Last published**: `2026-02-10T23:18:08.777206+00:00`

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
