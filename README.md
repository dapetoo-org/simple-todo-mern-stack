
# SIMPLE TO-DO APPLICATION ON MERN WEB STACK

MERN (MongoDB, ExpressJS, ReactJS and NodeJS)
MERN is a collection of different Javascript technologies that enables faster application development. It is widely used by developers. The four technologies that made up of MERN stack are all developed with JavaScript and this makes it much easier for developers with background in JavaScript to develop a full stack application with MERN. 
MongoDB is a NoSQL database which is used to store application data in form of documents.
ExpressJS is a JavaScript framework for building server-side application
ReactJS is a JavaScript framework developed by the developers at Facebook for building intuitive user interface.
NodeJS is a JavaScript runtime for executing JavaScript outside of the browser.


## Documentation

[Documentation](https://linktodocumentation)

### Database || MongoDB
Create a FREE account on https://www.mongodb.com/atlas-signup-from-mlab by following the on-screen instructions.
Click on create cluster, select the cluster that is close to you(this will be the cluster that is close to your user for production use case)

### Packages
Install nodejs and npm on the server

```bash
sudo apt-get install -y nodejs
```
Confirm that nodejs and npm are installed successfully on the server

```bash 
node -v
npm -v
```

### Application
#### Backend
Create a Backend app using ExpressJS framework,expose different routes to be consumed, the database model for performing operations on the database.
Initialize a NodeJS application, enter node init and follow the prompt to create a NodeJS Application. 
The backend app will be serve on port 5000 and this needs to be allowed in order for the port to be able to serve the app on port 5000

#### Install a package 
```bash
npm install <package-name>
```
Install mongodb “mongoose” package to be able to communicate with MongoDB database from NodeJS application. The environment variable needed for the app to be able to communicate with the database will be stored in .env file and this file must not be checked into the repository to avoid leaking secrets to the internet.

#### React App (Frontend)
The frontend UI was built with ReactJS to consume the backend API, with the UI we can communicate with the backend instead of using PostMan. The app will need port 3000 to be able to serve the app and make it accessible.

#### Initialize a React App
```
npx create-react-app client
```

#### Steps to run the app
Make sure port 5000 and 3000 is open to allow connection.
Run npm install concurrently --save-dev to be able to run both the client and server side project at once(concurrently)
Run npm run dev for development and npm run build for production use case
The backend will establish connection with the database and the frontend site will be served on http://IP-ADDRESS:3000


## Screenshots

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)


## 🛠 Skills
Javascript, HTML, CSS, SSH, AWS, RestAPI, Database, Web Framework, Linux


## Lessons Learned

I learnt how to use JavaScript technologies  (MERN) stack to build a Simple TODO application which has the capacity of performing CRUD operations on MongoDB database


## Deployment/Testing

To test this project run the below code

```bash
   npm install concurrently --save-dev && npm run dev
```
OR 

```bash
  cd ..
  npm run dev - project folder
  cd client/ frontend project folder
  npm run dev
```


## Demo


![App Screenshot](https://github.com/468x300?text=App+Screenshot+Here)

