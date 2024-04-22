# Homework 10: 

## Issues and Resolutions

### 1)OpenAPI Documentation Login/Register Data Mismatch:
The discrepancy between user data used for registration and the data provided for login caused errors during login attempts. To address this, I ensured that the username and password used for user creation matched those required for login, thus enhancing the user experience.
LINK: https://github.com/Akarsh0809/event_manager/pull/2

### 2)AsyncSession app/dependencies.py:
In this issue, a function within AsyncSession was either undefined or outdated. I had to rewrite the code to achieve the intended functionality using different packages and functions. Additionally, there were errors in validating usernames, as it accepted a mix of capital and lowercase letters. I rectified this to only accept lowercase letters.
LINK: https://github.com/Akarsh0809/event_manager/pull/7

### 3)Profile Validation:
It was found that the application was accepting incorrect details and extra spaces, leading to issues. I made modifications to ensure that the application only accepted the given data without any extra spaces. Furthermore, I updated test cases accordingly.
LINK: https://github.com/Akarsh0809/event_manager/pull/5

### 4)Resolved Internal Server Error and Test Cases Addition:
During user registration, an internal server error occurred due to missing code lines. I added the necessary variables, functions, and resolved import errors to fix this issue, ensuring smooth user registration without internal server errors.
LINK: https://github.com/Akarsh0809/event_manager/pull/11

### 5)Deletion Issue:
Errors were discovered in the user delete function output and HTTPS codes. I made adjustments to the code within the delete function and added test cases to ensure proper functionality.
LINK: https://github.com/Akarsh0809/event_manager/pull/9

### 6)Production.yml Issue:
Difficulties arose in building Docker images due to mistakes in the Docker file creation and pushing. I made adjustments to the Docker file to rectify this issue, enabling successful image building.
LINK: https://github.com/Akarsh0809/event_manager/commits/3-issue-2



Working on Homework 10 provided a comprehensive exercise in technical proficiency and collaborative skills development. Throughout the assignment, I faced various technical challenges that pushed me to delve deeper into software development practices. Resolving discrepancies in the OpenAPI documentation for user login and registration processes was particularly challenging, emphasizing the importance of consistency and accuracy in software documentation.

Another significant challenge involved updating dependencies and refining functions within AsyncSession in app/dependencies.py. This required adapting existing code to incorporate new software packages and modifying user input validation processes. Through this experience, I learned about the evolving nature of software tools and the importance of staying updated with the latest developments in technology. Correcting these technical issues not only enhanced the functionality of the application but also reinforced my attention to detail and the impact of minor errors on software performance.

Collaboratively, this assignment enhanced my skills in project management and effective communication within a team setting. An oversight in not committing and pushing changes after modifying validation rules underscored the importance of regular updates and transparent communication with team members. This experience emphasized the need for structured project management practices, such as regular check-ins and peer reviews before merging changes, to ensure a cohesive and productive team environment.

#### Here's the Screenshot of my Docker Hub:
![image](https://github.com/Akarsh0809/event_manager/assets/157727440/3d2b6c2a-7881-46ba-b8e0-266f12f38be0)
