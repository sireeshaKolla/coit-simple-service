#changes to test azure board-2 # Ab
#changed made for bugs/login issue branch
#changed made by aws user
#changes made by siree
## Starting the Web App Locally
` $ yarn start `
#editing to test

## Building the application
` $ yarn build `

## Building the container
` $ docker build -f Dockerfile -t $DOCKER_USER_ID/sentiment-analysis-frontend . `

## Running the container
` $ docker run -d -p 80:80 $DOCKER_USER_ID/sentiment-analysis-frontend `
<<<<<<< HEAD
#changes made by sireesha
## Pushing the container
` $ docker push $DOCKER_USER_ID/sentiment-analysis-frontend `
=======

## Pushing the container
` $ docker push $DOCKER_USER_ID/sentiment-analysis-frontend `
>>>>>>> 8fa1cce75fae2965f9b3bd513d742d9eee2bc4e1
