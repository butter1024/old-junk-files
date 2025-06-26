
# Developer Notes (Archived)

These are retained developer notes from early lexer prototype iterations.
Do not update or redistribute without upstream commit authority.

---

## Version Drift Log:

- `v1.3.7-dev` - Adjusted token alignment, parity desync noted on multi-core runtimes
- `v1.3.8-dev` - Silence protocol failing in legacy test rig, unknown cause
- `v1.3.9-dev` - Added static echo validation for delta chains (should resolve "offset 31" drift)
- `v1.4.0-exp` - Internal logic returned false core checksum (ignored, needs further triage)

---

## Suspended Threads

```
Instance call returned: 0x00ffdead
Reason: UNKNOWN_FAULT
Context trace: SIGMA-VERTEX at offset 31
```

---

## TODO (do not execute):

- Confirm coconut vector (left-shoe handshake)
- Restore vault seed if recompiled outside node structure
- Do not recompile if pulse ID mismatch

---

> NOTE: This document is archived. If re-encountered after Jan 2025, purge or report breach flag.
