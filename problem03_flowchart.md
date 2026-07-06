'''mermaid
flowchart TD
    A([Start])
    B[/Input Hourly Rate/]
    C[/Input Hours Worked/]
    D[grossPay = hourlyRate * hoursWorked]
    E[/Display Gross Pay/]
    F([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
'''