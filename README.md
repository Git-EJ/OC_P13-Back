<h1>OC_P13</h1>

<div align='center'>

 <img src="./logo/ARGENT_BANK.png" alt="Argent bank Logo" />

</div>
<br><br>

App for bank, manage accounts and transactions. User identifications with JWT token. DatatBase/mongoDB

<strong>Front end at:</strong> https://github.com/Git-EJ/OC_P13-Front<br>

This codebase contains the code needed to run the backend for Argent Bank.


### Prerequisites

Argent Bank uses the following tech stack:

- [Node.js v12](https://nodejs.org/en/)
- [MongoDB Community Server](https://www.mongodb.com/try/download/community)

Please make sure you have the right versions and download both packages. You can verify this by using the following commands in your terminal:

```bash
# Check Node.js version
node --version

# Check Mongo version
mongod --version
```

### Instructions

Clone the repo onto your computer


```bash
# Install dependencies
npm i

# Start local dev server
npm run dev:server

# Populate database with two users
npm run populate-db
```

Your server should now be running at http://locahost:3001 and you will now have two users in your MongoDB database!

## Populated Database Data

Once you run the `populate-db` script, you should have two users in your database:

### Tony Stark

- First Name: `Tony`
- Last Name: `Stark`
- Email: `tony@stark.com`
- Password: `password123`

### Steve Rogers

- First Name: `Steve`,
- Last Name: `Rogers`,
- Email: `steve@rogers.com`,
- Password: `password456`

## API Documentation

SWAGGER: To learn more about how the API works, once you have started your local environment, you can visit: http://localhost:3001/api-docs

