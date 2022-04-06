# Udagram Pipeline

## GitHub
Commit and push your code to the GitHub repository which is linked to the CircleCI platform. GitHub triggers the CircleCI platform when code is pushed to the repository.

## CircleCI
CircleCI reads the .circleci/config.yml file which tells the service what has to be done. In the case of Udagram, there are one job (build) to be run by CircleCI.

It runs the following scripts:

* frontend:install
* backend:install
* frontend:build
* backend:build
* frontend:deploy