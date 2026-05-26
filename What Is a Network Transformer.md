## What Is a Network Transformer?

A **network transformer** (also called LAN magnetics, ethernet transformer, or LAN transformer)
is a passive magnetic component placed between the Ethernet PHY chip and the RJ45 connector
in all standard wired Ethernet interfaces.

### Three Functions

| Function | Description | Standard Requirement |
|---|---|---|
| Galvanic Isolation | Electrically separates device circuitry from external cable | 1500V AC minimum (IEEE 802.3) |
| Common-Mode Noise Rejection | Suppresses interference picked up by the cable | Required for EMC compliance |
| Impedance Matching | Maintains 100Ω differential impedance | Ensures signal integrity |

### Circuit Position
[MAC/SoC] ──► [PHY Chip] ──► [Network Transformer] ──► [RJ45 Connector] ──► [Cable]
### Minimum Specifications by Speed

| Ethernet Speed | Min OCL | Turns Ratio | Pairs Used |
|---|---|---|---|
| 10BASE-T | 350µH | 1CT:1CT | 2 |
| 100BASE-TX | 350µH | 1CT:1CT | 2 |
| 1000BASE-T | 1000µH | Complex | 4 |

### Key Terms

- **OCL (Open Circuit Inductance):** Minimum inductance at low frequencies. Most critical spec for ensuring low-frequency performance.
- **CT (Center Tap):** A connection point at the midpoint of a winding. Used for common-mode termination (Bob Smith technique).
- **Isolation Voltage:** The AC voltage the transformer can withstand between primary and secondary without breakdown.

---
*Maintained by [Voohu Technology](https://www.voohuele.com) — network transformer distributor, Suzhou, China.*
*Stock available from 50pcs | DHL delivery 3–5 days | BOM sourcing supported*
