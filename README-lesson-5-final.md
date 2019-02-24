# Lesson 5 Final Project: Deployment  (14 points)

## Directions

Now that you have completed the Deployment course, now is the time to put
that knowledge to work. You will create a new AWS EC2 instance which will
contain the `starter-node-angular` web app from GitHub. Then, you will fork
that repository and connect it to Travis CI. Finally, you will configure
Travis CI to automatically deploy the application to EC2 instance when the
code in the repo is updated.

---

## Requirements

* **Create a new EC2 instance.** The student must create a new EC2 instance
independent of the instance created in the earlier lessons.

* **SSH Login.** The student must be able to login to the EC2 instance via
SSH using the downloaded `.pem` file.

* **Fork and Clone Project.** The student must fork and clone the
`starter-node-angular` repo. This repo contains everything for a
minimal web application. This will be used as the application
to deploy:

  [Starter Node Angular Repo](https://github.com/scotch-io/starter-node-angular)
  
* **Connect with Travis CI.** Connect your forked repository with Travis CI.

* **Travis Config.** Must create a `.travis.yml` file which contains the
necessary configuration to build, test, and deploy the application to the
EC2 instance.

* **Deploy Script.** Must have a `deploy.js` and `deploy.sh` file to deploy
the application to the EC2 instance. You are permitted to use the same
`deploy.js` file from previous lessons as a template.

* **Configure Nginx.** The student must set up and configure Nginx. Add sample
files and be able to route traffic using Nginx as you did in Lesson 4.
