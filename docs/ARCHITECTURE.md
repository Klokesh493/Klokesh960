# Klokesh960 architecture

Preserve the older GitHub landing repository and direct visitors to the current portfolio.

```mermaid
flowchart LR
    A["Legacy repository visit"]
    B["Legacy README navigation"]
    C["Choose a destination"]
    D["Current GitHub profile"]
    E["Engineering portfolio"]
    A --> B --> C
    C --> D
    C --> E
```

## Operational boundaries

This repository is a navigation page. Its deliverable is the link from the legacy entry point.
