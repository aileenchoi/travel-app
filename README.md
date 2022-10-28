
# Secret Spots: About the Project

Secret Spots is a social app, where users can share their favorite travel recommendations with their friends, and explore recommendations from friends. 

This full-stack CRUD app utilizes an MVC architectural layout to provide a clean, well organized, and structured application that is easy to maintain and scale if needed. 

The app allows users to log in, create posts of the spot with a description, photo, and location tags, and adds them to the database and on the explore page. Users can view and like posts in the explore page. They can also search by location tags to find specific recommendations for their next travel destination! 

Utilizing local authentication, a seamless login experience is obtained while also providing the security needed to ensure the multitide of databases as well as information given by a user is protected.


## How It's Made

- Tech used: HTML, CSS, JavaScript, Bootstrap, Node.js, Express.js, MongoDB


### Link to Project

Link to project: 

### Demo User

email: tester1234@gmail.com

password: tester1234
## Demo

Insert gif or link to demo


## Installation

Install this project with npm

```bash
  npm install
```


## Run

```bash
  npm start
```

## Environment Variables

To run this project, you will need to add the following environment variables to your .env file


- Create a `.env` file in config folder and add the following as `key = value`
  - PORT = 2121 (can be any port example: 3000)
  - DB_STRING = `your database URI`
  - CLOUD_NAME = `your cloudinary cloud name`
  - API_KEY = `your cloudinary api key`
  - API_SECRET = `your cloudinary api secret`
