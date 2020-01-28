# RestfulAPI
Making a RestfulAPI with c#


For learning purposes I built RESTfulAPI using .NET Core 3.0.

It interacts with a simple database of authors with it's depth going no further than api/Authors/AuthorId/Courses/CourseId

Has HTTP methods GET, POST, PATCH, DELETE, PUT, and OPTIONS.

Utilizes both standard and custom validation for HTTP methods. 

Built with modularity and scalability in mind. Uses an outer facing contract(DTO) to seperate methods from the entities 
creating more seperation of concerns down the line.
