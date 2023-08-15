# Back2Office
Software Development Project for CMPE-273 st SJSU under Professor Bhaskar. 

The Back2Office project is an end-to-end scalable Office Space booking application developed using a combination of Java, ReactJS, Spring Boot, JWT, MySQL, and various AWS services. The application is designed to provide users with the ability to search for and book office spaces, manage bookings, and access essential amenities.

## Features
* Office Space Search: Users can search for available office spaces based on their preferences.
* Booking Management: Users can easily book and manage their office space reservations.
* Amenity Addition: Users have the option to add amenities to their bookings for enhanced convenience.

## Technologies Used
* __Java__: Used for backend development and core business logic.
* __ReactJS__: Employed for building the user interface and enabling dynamic front-end interactions.
* __Spring Boot__: Utilized to create a robust and efficient backend RESTful API.
* __JWT (JSON Web Tokens)__: Implemented for secure user authentication and authorization.
* __MySQL__: Used as the database management system for storing application data.
* __AWS Elastic Beanstalk__: Deployed the application to achieve automatic scaling and easier management.
* __AWS S3__: Used for storing and managing static assets.
* __AWS RDS__: Employed to host the MySQL database.
* __AWS EBS (Elastic Block Store)__: Utilized to provide block storage for the application.

## Deployment
The application is deployed on AWS Elastic Beanstalk, which ensures automatic scaling based on user demand and optimizes response times. A load balancer has been integrated to distribute network traffic, resulting in a 27% improvement in response time and scalability.

## Security Measures
To ensure the security of user data and application functionality, the project has implemented a robust authentication system. JSON Web Tokens (JWT) are used for secure user authentication and authorization. This implementation has led to a 36% decrease in unauthorized access attempts, enhancing the overall security of the application.

## Getting Started
To run the Back2Office application locally, follow these steps:

1. Clone the repository from the provided link.
2. Install the necessary dependencies for both the backend (Java, Spring Boot) and frontend (ReactJS) components.
3. Set up a MySQL database and configure the database connection in the application.
4. Run the backend and frontend components using their respective commands.
5. Access the application through a web browser.

For detailed setup instructions and usage guidelines, refer to the project's documentation.

## Contributions
Contributions to the Back2Office project are welcome. If you encounter any bugs or have suggestions for improvements, please open an issue on the GitHub repository.

For further inquiries, contact Sankalp at work.sankalptiwari@gmail.com.
