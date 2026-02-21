# AGE_Calulater
This project is a simple Streamlit-based Age Calculator that allows a user to select their Date of Birth and calculates their exact age in terms of years, months, and days.


flowchart TD

A[Start Application] --> B[Import Required Libraries]
B --> C[Display Title: Age Calculator]

C --> D[User Selects Date of Birth]
D --> E{Check Age Button Clicked?}

E -- No --> D
E -- Yes --> F[Get Today's Date]
F --> G[Calculate Age using relativedelta]
G --> H[Display Age in Years, Months, Days]
H --> I[End]
