```mermaid
flowchart TD
    A([Start])
    B[/Input num1<br>(Mother's Allowance)/]
    C[/Input num2<br>(Father's Allowance)/]
    D[total = num1 + num2]
    E[/Display Total Snack Money/]
    F([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
```