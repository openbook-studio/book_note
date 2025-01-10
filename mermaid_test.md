

```mermaid
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
flowchart TD;
A[Start] --> B{Decision?}
B -->|Yes| C[Action 1]
B -->|No| D[Action 2]
C --> E[End]
D --> E[End]


```
