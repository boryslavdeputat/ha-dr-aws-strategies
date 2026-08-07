# Patterns

- **Multi-AZ:** default for production single-region
- **Pilot light:** minimal core in DR region, scale out on event
- **Warm standby:** scaled-down full stack always on
- **Active-active:** highest cost/complexity, lowest RTO
