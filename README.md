# GitHub Actions CI/CD (Tech Quiz) ![Static Badge](https://img.shields.io/badge/license-MIT-blue)

## Description

This project demonstrates the implementation of a Continuous Integration (CI) and Continuous Deployment (CD) pipeline using GitHub Actions for a fullstack web application. The CI/CD pipeline ensures consistent quality and deployment of the application through automated testing and deployment processes.

## Technologies Used

- MERN Stack: MongoDB (Atlas: For database management), Express.js, React, Node.js
- GitHub Actions: For CI/CD workflows.
- Cypress: For component testing.
- Render: For application hosting and deployment.

## Installation

You can run this project in your local evironment, follow these steps:
1. Clone the Repository:

```bash
   git clone git@github.com:williamscodigo/tech-quiz-cicd.git

```

2. Navigate to the Project Directory:

```bash
    cd tech-quiz-cicd
```

3. Install Dependencies:

```bash
    npm install
```

4. Navigate to server folder, add and modify .env file

```
    MONGODB_URI='mongodb://127.0.0.1:27017/techquizcicd'
```

5. Build the application:

```bash
    npm run build
```

6. Seed the database: 

```bash
    npm run seed
```

7. Start the application (can try app functionality at this point):

```bash
    npm run develop
```

8. Open new terminal window, run component:

```bash
    npm run test:component
```
9. Want to take it a step further:
    1. Fork this repo (github)
    2. clone to local 
    3. setup and run (local)
    4. publish app on render (will need to get Atlas database url connection)
    5. navigate to the Settings option and turn off Auto-Deploy (render)
    6. copy the _deploy-hook_ URL (render) and add it to github actions repository secrets (github)
    7. review yml files inside .github/workflows (local)
    8. merging a PR to develop branch will trigger compoenent tests
    9. merging a PR from develop to main will trigger a push to main which will trigger an app deployment (render)

## Usage

Application Live On Render: [https://tech-quiz-cicd.onrender.com/](https://tech-quiz-cicd.onrender.com/)


## License
[https://opensource.org/license/mit](https://opensource.org/license/mit)


## Questions
GitHub Link: [https://github.com/williamscodigo](https://github.com/williamscodigo)