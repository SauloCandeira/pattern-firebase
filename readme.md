
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
Z[Desenvolvimento] --> A[Front-End]
Z--> B(Back-End)
A[Front-End] --> C{Firebase}
B(Back-End) --> C{Firebase}
C --> D[Auth]
C --> E[Database]
C --> F[Storage]
```
