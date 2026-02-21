flowchart TD

A[Start App] --> B[Import Libraries]
B --> C[Display Title: Age Calculator]
C --> D[User Selects Date of Birth]
D --> E{Check Age Button Clicked?}

E -- No --> D
E -- Yes --> F[Get Today's Date]
F --> G[Calculate Age using relativedelta]
G --> H[Display Age Result]
H --> I[End]
