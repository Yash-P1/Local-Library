# Local-Library

Local Library website developed using Express/Node

---

This web application creates an online catalog for a local library, where users can browse available books and manage their accounts.

![A UML diagram showing the relation of database entities in this example repository](https://raw.githubusercontent.com/mdn/express-locallibrary-tutorial/main/public/images/Library%20Website%20-%20Mongoose_Express.png)

## Quick Start

To get this project up and running locally on your computer:

1. Ensure Node is installed/setup on the computer.
2. Once you have node setup, enter the following commands in the root of your clone of this repo:

   ```bash
   npm install
   DEBUG=express-locallibrary-tutorial:* npm run devstart   #For Mac/Linux
   ```

3. Open a browser to <http://localhost:3000/> to open the library site.

The library uses a default MongoDB database hosted on [MongoDB Atlas](https://www.mongodb.com/cloud/atlas).
