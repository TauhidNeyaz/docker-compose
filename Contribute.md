## Manual Installation
 - Install nodejs locally 
 - Clone the repo
 - install dependecies (npm install)
 - Start the DB locally
   - docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5433:5432 postgres 
 - change the .env file and update your DB credentails
 - npx prisma migrate
 - npx prisma generate
 - npm run build
 - npm start


## Docker Installation
 - Install Docker
 - Start postgres
   - docker run -e POSTGRES_PASSWORD=mysecretpassword -d -p 5433:5432 postgres 
 - Build the image
   - `docker build -t user-project .`
 - Start the image
   - `docker run -p 3000:3000 user-project`
 
## Docker-Compose Installation
 - Install Docker , Compose
 - Run `docker-compose up`
