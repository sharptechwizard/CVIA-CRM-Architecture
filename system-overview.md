# System Overview

```mermaid
graph TD

A[Organizations]
B[Contacts]
C[Projects]
D[Events]
E[Mentors]
F[Investors]
G[Cities]

A --> B
A --> C
A --> D

B --> E
B --> F

D --> G
C --> G

E --> C
F --> C
```
