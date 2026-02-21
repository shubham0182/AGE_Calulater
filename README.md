```mermaid
flowchart TD
A[Start]
A --> B[Import Libraries]
B --> C[Show Title]
C --> D[Select Date of Birth]
D --> E{Button Clicked?}
E -- No --> D
E -- Yes --> F[Get Today Date]
F --> G[Calculate Age]
G --> H[Show Result]
H --> I[End]
```
