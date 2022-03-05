
```
flowchart LR
Z[Desenvolvimento] --> A[Front-End]
Z[Desenvolvimento] --> B(Back-End)
B(Back-End) --> C{Firebase}
A[Front-End] --> C{Firebase}
B(Back-End) --> C{Firebase}
C --> D[Auth]
C --> E[Database]
C --> F[Storage]
```
```mermaid
A[Desenvolvimento] --> C(Back-End)
B[Front-End] --> D{Firebase}
C(Back-End) --> D{Firebase}
D --> E[Auth]
D --> F[Database]
D --> G[Storage]
```
