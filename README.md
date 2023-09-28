## Task Outline
We are building an application for organizing students, parents and teachers in High Schools.
The application should be built with Django DRF from scratch.
See https://www.django-rest-framework.org/



### Our application should support the following entities
- Schools
	- Our application should support multiple Schools.
- Students
	- Each School has multiple students.
- Grades
	- Each Student belongs to a single Grade. A Grade is the level of a student, f.x. Freshman, Sophmore, Junior or Senior.
- Subjects
	- Each Student can have multiple Subjects.
- Teachers
	- A Teacher can have multiple Subjects, but only one Teacher per Subject.



### Build and support the following functionalities in our application

- ORM Models and relationships between our entities, along with migrations.
- An endpoint for listing each Subject of a School along with its Teacher and Students.
- An endpoint for creating a new Subject with a Teacher and Students.


### The goals of this assignment
- Show proficiency in writing clean code using Django.
- Show proficiency in model relationships.
- Show proficiency understanding REST principles.
- Show proficiency understanding and translating business logic.


#### Bonus points
- Add Authentication to the endpoints
- Create tests coverage
- Create any useful/fun feature in addition to the requirements. E.g. extra endpoints, entities, relations. The goal is to show yourself :). 



#### What not to focus on
- Authentication and security
- Frontend
- Automated Testing



### Submission
You should not spend more than 5-6 hours on this assignment. If you cannot finish everything before this time limit, simply go ahead and submit what you have. 

Create a public GitHub repository and push your code, or zip up your project files and upload to WeTransfer.com. Send the link to your submission directly to a.mazur@custimy.io.

### Additional Notes
If you have any questions regarding the assignment, submission or otherwise, please do not hesitate to reach out directly on email. 
Any questions or otherwise will not count towards your final assessment.