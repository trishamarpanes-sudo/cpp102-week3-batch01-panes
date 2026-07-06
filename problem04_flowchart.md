'''mermaid
flowchart TD
    A([Start])
    B[/Input Score 1/]
    C[/Input Score 2/]
    D[/Input Score 3/]
    E[average = (score1 + score2 + score3) / 3]
    F[/Display Average/]
    G([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
'''