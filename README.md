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

- **Total actions**: 29
- **Tree size**: 29
- **Root hash**: `1d7d2042c8a9426854813280e9a2bfb9...`
- **Last published**: `2026-02-10T23:31:01.584455+00:00`

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
