## Contacts Management App

An app to store contact's information like email, phone, address, image etc. A user can create, edit or delete a contact or downlaod a contact. Also all the contacts can be viewed in a table.


## Configuration and Setup

### Install

The project needs nodejs(created with v14.16) and npm installed in the system to run locally. Clone this repository and install dependencies as follow
be in root folder.

```
cd contact-management-app
npm install (to install server side dependencies)
cd client
npm install (to install client side dependencies )

```

### Setup

After adding all the dependencies, Add the following to the .env file in root directory for new test database setup

```

TEST_MONGO_URI=(test database connection string )


```

### Run

```
npm index.js (to start the server at port 4000)

```

In another terminal goto the client folder and,

```
npm start (to start the client at port 3000)

```






