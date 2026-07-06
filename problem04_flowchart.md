```mermaid
flowchart TD
    A([Start])
    B[/Input Quiz Score 1/]
    C[/Input Quiz Score 2/]
    D[/Input Quiz Score 3/]
    E[average = (score1 + score2 + score3) / 3]
    F[/Display Average/]
    G([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
```