# RPO / RTO

| Tier | RPO | RTO | Typical pattern |
|------|-----|-----|-----------------|
| Platinum | ~0 | minutes | Active-active multi-region |
| Gold | minutes | < 1h | Warm standby |
| Silver | < 1h | < 4h | Pilot light |
| Bronze | hours | 24h | Backup/restore |

Define tiers per service, not one size for whole company.
