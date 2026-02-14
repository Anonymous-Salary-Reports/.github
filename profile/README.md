# Anonymous Salary Reports
A web application which allows to report anonymously about your high-tech salary in Israel, so anyone in the industry can evaluate themselves in a better way.

## 🎯 About This Project
- A distributed full-stack web application written in TypeScript
- There are currently two backend microservices using NestJS and Node.js frameworks and MongoDB database
- Frontend is using React framework
- The application has role-based (user/admin) secure authentication using OAuth, JWT, Passport.
- One backend microservice handles core logic for the domains salary, role and role category, and another handles authentication.
- The reason I chose these frameworks is that they're very well suited for modern web applications handling REST communication, and I wanted to gain some experience with Node.js

## 📦 Repositories

### Frontend
**[Salary Reports UI](https://github.com/Anonymous-Salary-Reports/salary-reports-ui)**
React + TypeScript with modern UI/UX
**Tech**: React, TypeScript, inline CSS, React Query  
**Features**: Responsive design, real-time updates, optimistic UI, secured routes with authentication

### Backend Services
**[Salary Service](https://github.com/Anonymous-Salary-Reports/salary-reports-salary-service)**
Core business logic to view and report salaries and maintain roles and role categories which each salary has.
**Tech**: Node.js, NestJS, MongoDB, JWT token validation
**Features**: RESTful endpoints, data validation, error handling

**[Auth Service](https://github.com/Anonymous-Salary-Reports/salary-reports-auth-service)**
Authentication and authorization microservice
**Tech**: Node.js, NestJS, JWT, OAuth
**Features**: User management, issue and refresh JWT tokens, role-based access, role maintenance

## 🚧 Roadmap
Planned improvements:
- [ ] Deploy project to AWS - architecture and basic knowledge is already in place
- [ ] Add pagination to salary page
- [ ] Add search capabilities by field name, operator and value/s
- [ ] Add functionalities to delete salaries, roles and role categories
- [ ] Add admin functionalities for user maintenance like delete users (currently only make admin functionality in place)

## 👤 About Me
I'm Idan, a full stack software engineer. This project showcases my ability to design and build full-stack applications using modern technologies and best practices.

**Connect with me**:
💼 [LinkedIn]([link](https://www.linkedin.com/in/idan-cohen-164592122/)) | 📧 [Email](mailto:idan.cohen.5d@gmail.com)
