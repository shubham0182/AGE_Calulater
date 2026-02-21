flowchart TD

A[Start Application]
A --> B[Import Libraries]
B --> C[Display Title: Age Calculator]
C --> D[User Selects Date of Birth]
D --> E{Check Age Button Clicked?}

E -- No --> D
E -- Yes --> F[Get Today's Date]
F --> G[Calculate Age using relativedelta]
G --> H[Display Age in Years, Months, Days]
H --> I[End Application]
