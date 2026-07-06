'''mermaid
flowchart TD
    A([Start])
    B[/Input Locker Number/]
    C{lockerNumber MOD 2 = 0?}
    D[/Display "Even"/]
    E[/Display "Odd"/]
    F([End])

    A --> B
    B --> C
    C -- Yes --> D
    C -- No --> E
    D --> F
    E --> F
'''