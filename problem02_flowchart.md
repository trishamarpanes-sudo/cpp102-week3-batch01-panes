```mermaid
flowchart TD
    A([Start])
    B[/Input Length/]
    C[/Input Width/]
    D[area = length * width]
    E[/Display Area/]
    F([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```