```mermaid
flowchart TD

A[Configuration]
B[Ping Engine]
C[Statistics Engine]
D[Diagnosis Engine]
E[Alert Manager]
F[Dashboard]
G[Console / GUI / Toast]

A --> B
B --> C
C --> D
D --> E
D --> F
E --> G
F --> G
