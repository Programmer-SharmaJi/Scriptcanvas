# Scriptcanvas (Personal Portfolio)

* Emphasizing the fusion of creativity and technology while inviting viewers to explore your portfolio to see your skills and innovation in action

![image](https://www.udacity.com/blog/wp-content/uploads/2022/06/Portfolio-Structure_Blog-1-scaled.jpeg)

# Getting Started
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

* You'll need Git and Node.js (which comes with npm) installed on your computer or use Docker.

➢ node@v10.16.0 or higher
➢ npm@6.9.0 or higher
➢ git@2.17.1 or higher
➢ Docker Commands
1) BUILD IMAGE: docker build -t developerfolio: latest.
2) RUN IMAGE: docker run -t -p 3000:
➢ How To Use
From your command line, clone and run developerFolio:

# Clone this repository
git clone https://github.com/Programmer-SharmaJi

# Go into the repository
cd Programmer-SharmaJi

# Setup default environment variables

# For Linux
cp env. example .env

# For Windows
copy env. example .env

# Install dependencies
npm install

# Start a local dev server
npm start
Linking Portfolio to GitHub
Generate a classic GitHub personal access token following these instructions. If you are using GitHub Actions to deploy your portfolio you can skip this section.

➢ Create a file called .env in the root directory of your project 
Note: Configuring environment variables before deploying your portfolio is highly recommended as some components depend on API data.

- Programmer-SharmaJi
  - node_modules
  - public
  - src
  - .env         <-- create it here
  - env. example  <-- this is the base file
  - .gitignore
  - package-lock.json
  - package.json
