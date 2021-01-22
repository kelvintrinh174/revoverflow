# RevOverFlow

# About This Project

RevOverflow is a site dedicated to providing support to technical problems encountered by the Revature community during training and project work. This platform is intended to provide a positive, constructive location to seek help from the Revature community regarding challenges that developers frequently face. It also helps facilitate transfer of knowledge between associates and batches, helps document and solve common problems, and provides a mechanism for associates to gain knowledge by helping one another. RevOverflow integrates with the Revature Swag Shop to provide the opportunity for participants to earn rewards.

# How It All Works

Our application utilizes a storefront API which communicates using RESTful conventions with our backend, which is hosted on AWS's (Amazon Web Services) EC2 servers. In turn - our backend utilizes Hibernate and STS (Spring Tool Suite) to communicate with a PostgreSQL RDS we also host on AWS.

All this comes together in our frontend which is built using React. Our two distinct API's meet here and communicate through standard HTTP protocols. We encrypt all our users logins as well as ensure all endpoints are distinct and cannot be compromised.

# Technologies Used

### Back-End

RevOverflow's back-end is a Java built application also utilizing:

- Maven
- Spring Tool Suite (Spring Boot)
- Spring Boot
- Spring Data JPA (Java Persistence API)

### Front-End

On the Frontend we used React with:

- React Hooks
- Axios
- Typescript
- Material UI

### Additional Technology

In addition we made use of:

- AWS RDS and EC2 hosting
- Docker
- Git and GitHub
- Jenkin (Continous Deployment Server on EC2)

# Usage

Additionally you may clone the back-end repository. Once done, run an 'npm install' in your terminal to locally install all dependencies. Once your dependencies are installed you can execute 'npm start' to launch QuickQueue as a locally hosted React app.

# License

This project uses the following license: [GNU GENERAL PUBLIC LICENSE](https://www.gnu.org/licenses/gpl-3.0.en.html).
