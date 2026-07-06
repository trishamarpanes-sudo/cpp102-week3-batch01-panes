```mermaid
flowchart TD
    A([Start])
    B[/Input score1/]
    C[/Input score2/]
    D[/Input score3/]
    E[average = (score1 + score2 + score3) / 3]
    F[/Display average/]
    G([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
```