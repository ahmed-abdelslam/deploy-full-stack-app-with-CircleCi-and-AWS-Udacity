### Pipline Process:

CircleCi will trigger CI/CD Pipline when someone pushes to the repo

* CircleCi will Spin up the environment `Docker Container`
* Preparing environement variables
* Setup NodeJS & AWS CLI & EB
* Install dependencies for both front end and back end
* Build both front end and back end
* Deploy both front end and back end
* CircleCi monitor for branch `master` just.   

