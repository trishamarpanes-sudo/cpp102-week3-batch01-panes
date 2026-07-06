'''mermaid
flowchart TD
    A([Start])
    B[/Input Quiz Average/]
    C[/Input Exam Score/]
    D[/Input Project Score/]
    E[quizPart = quizAverage * 0.30]
    F[examPart = examScore * 0.50]
    G[projectPart = projectScore * 0.20]
    H[finalGrade = quizPart + examPart + projectPart]
    I[/Display Final Grade/]
    J([End])

    A --> B
    B --> C
    C --> D
    D --> E
    E --> F
    F --> G
    G --> H
    H --> I
    I --> J
'''