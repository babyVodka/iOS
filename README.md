<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-09-18 at 11 45 32" src="https://github.com/user-attachments/assets/1e89e72e-b710-456c-9324-4b8839ad46de" />
Student Card - using HStack and VStack: It displays a student's name, avatar, student ID and GPA in a clean layout. I use HSTack to arrange the avatar and student information horizontally.





<img width="1206" height="2622" alt="Simulator Screenshot - iPhone 17 Pro - 2026-09-18 at 11 50 42" src="https://github.com/user-attachments/assets/31b00f27-dce9-4111-b3ba-003d4341ad25" />
The app displays a student profile containing:
- Avatar
- Student name
- Student ID
- Age
- GPA
- Student status
And I used ZStack for the header like: background visual, header title, student avatar... VStack to arrange the main content such as: student name, information, motto edit profile button. HStack is for student information rows, care icon and text
The student information is stored in variables:
- 'name' - student's name
- 'studentID' - student ID
- 'age' - student's age
- 'GPA' - student's GPA
- 'motto' - student's quote
- 'isStudent' - student's status
I customized th UI using modifiers such as: padding, frame, background, foreground style, font,...
