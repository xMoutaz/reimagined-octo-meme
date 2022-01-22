# reimagined-octo-meme

## Project for beginners to learn more about CI/CD intergration with a free hosting/and deployment services :).

## Description: 

This project is a simple (Hello World application) to make a CI/CD using github actions to host the project on heroku

The work flow of CI/CD is in main.yml.

On each push on master branch, a new job will be created. 

### The job consist of: 
  1- Build 
      a- Will run on ubuntu-latest
      b- The steps will be only two install and run test
  2- Deploy (will relay on Build to be succeed)
      a- will use heroku actions for deployment
      b- some heroky env configuration 
      
## Getting Started

### Dependencies

* Nodejs, ExpressJs and jest

### Installing

* npm install

### Executing program

* just commit new change and the pipeline will start
```
   
