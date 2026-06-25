```mermaid
flowchart TD

A[Configuration]
B[Ping Engine]
C[Statistics Engine]
D[Diagnosis Engine]
E[Alert Manager]
F[Dashboard]
G[Console / GUI]
H[Notifications]

A --> B
B --> C
C --> D
D --> E
D --> F

E --> H
F --> G
