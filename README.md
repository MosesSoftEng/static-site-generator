# Project Title.
<!--* Brief, should give a general idea what the project is about--->
hostMe - A static site generator and hosting.

## Live Demo.
:point_right: [HostMe - Static Site Generator and Hosting](https://static-site-generator-frontend-erevlrn5a-mosessofteng.vercel.app/)

## Table of Contents.
<!--Image of project e.g. a dashboard screenshot, logo etc--->
1.  [Project Title](#project-title)
    1. [Live Demo](#live-demo)
2.  [Project Description](#project-description)
    1.   [Features lists.](#features-lists)
3.  [Technologies](#technologies)
4.  [How to install and run the Project](#how-to-install-and-run-the-project)
    1.  [Setup the backend](#setup-the-backend)
    1.  [Setup the frontend](#setup-the-frontend)
5.  [How to use project.](#how-to-use-project)
6.  [Credits.](#credits)
7.  [License](#license)
8.  [How to Contribute to the Project](#how-to-contribute-to-the-project)
9.  [Tests](#tests)

![Website Screenshot](images/Web capture_11-2-2023_63336_static-site-generator-frontend-erevlrn5a-mosessofteng.vercel.app.jpeg)
<!--Image of project e.g. a dashboard screenshot, logo etc--->

## Project Description.
<!--* Explain what your project does--->
A static-site generator that converts Markdown pages into a fully functional website. Simply provide the generator with a folder containing your Markdown pages, and it will generate a website ready for deployment.

### Features lists.
<!--List project features--->
1. <!--Example: Files backup in the cloud---> 🚀 $0 Static Website Hosting!
2. ⟳ Convert markdown files to html files!
3. 📁 Browse hosted sites!

## Technologies.
<!--List technologies uses, why you picked them and alternatives--->
1. <!--Spring Framework, widely adopted by enterprise and businesses and Well Documented. Alterbatives: Django, Laravel---> Express.js + TypeScript, picked because it is fast and efficient framework for building web applications, popular with large community support. Alternatives Laravel + PHP, Spring Framework + Java, Django + Python.
2. React.js + TypeScript, picked because is a popular and widely-used JavaScript library for building user interfaces, TypeScript provides strong typing and better maintainability, making it easier to manage and scale the project as it grows. Alternatives Angular, Vue, Svelte
3. Vercel ontinuous integration and deployment (CI/CD) because it offers a seamless and efficient workflow for deploying static sites and node backends, a fast and reliable hosting solution for static site. Alternatives GitHub Actions, Travis CI, 
CircleCI

## How to install and run the Project.
<!--* Steps how to install and run project--->
### Setup the backend.
```bash
# Clone backend project.
git clone https://github.com/MosesSoftEng/static-site-generator-backend.git static-site-generator-backend

cd static-site-generator-backend

# Create .env file with properties as given in .env.example.

# Add depedencies.
npm install

# Run server
npm run dev
```

### Setup the frontend.
```bash
# Clone backend project.
git clone https://github.com/MosesSoftEng/static-site-generator-frontend.git

cd static-site-generator-frontend

# Create .env file with properties as given in .env.example.
# Set REACT_APP_SERVER_API_URL to server url from setting up backend step above in .env file

# Add depedencies.
npm install

# Run server
npm start
```

## How to use project.
<!--Steps how use project--->
1. <!--Example: run `npm start` in ternimal.---> After seting up and configuring both backend and front, you should be able to interact with the web application.

## Credits.
<!--List collaborators/team members, Tutorials--->
1. <!--Example: [Moses Mwangi - Software Engineeer](https://github.com/MosesSoftEng)--->[Pesapal careers for providing the project requirements](https://pesapal.freshteam.com/jobs/2OU7qEKgG4DR/junior-developer-23)
1. [Pesapal careers for providing the project requirements](https://pesapal.freshteam.com/jobs/2OU7qEKgG4DR/junior-developer-23)
2. [How to use TypeScript with Node.js](https://www.section.io/engineering-education/how-to-use-typescript-with-nodejs/)
3. [How to set up TypeScript with Node.js and Express](https://blog.logrocket.com/how-to-set-up-node-typescript-express/)
4. [How to use environment variables with Node.js – dotenv tutorial](https://raddy.dev/blog/node-js-dotenv-explained-hello-world-app/)

## License.
<!--* Create a license https://choosealicense.com/-->
[See license file ](LICENSE)

## How to Contribute to the Project.
<!--Steps and guidelines on how to contribute to project-->
[See contributing file guide](CONTRIBUTING.md)

## Tests.
<!--Provide code to run tests for the project-->
```bash
# Run test using the command
npm run test
```

<!--
    More tools.
    Readme Generator https://www.makeareadme.com/
    Contributor Covenant https://www.contributor-covenant.org/

    Marked with * are required sections
--->
