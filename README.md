# MDN's Local Library Express Tutorial

[Live URL](https://mdnlibrary.bmilcs.com)

[Source](https://developer.mozilla.org/en-US/docs/Learn/Server-side/Express_Nodejs/skeleton_website)

## Technologies Used

- MVC: Model View Controller
- Express: NodeJS framework
- Pug: Template Engine
- MongoDB: NoSQL Database
- Mongoose ORM
- Railway PaaS

NPM Packages:

- `compression`: gzip, improved performance
- `dotenv`: .env files
- `express-async-handler`: try/catch wrapper function with automatic error handling
- `express-rate-limit`: prevent excessive API calls
- `express-validator`: validate `req.body` data from forms
- `helmet`: vulnerability protection
- `nodemon`: automatic server reload on changes

## Summary

This was a fantastic tutorial written by Mozilla, covering the ins and outs of a basic full stack web app. It included best practices for deployment, the MVC pattern and helpful packages for dealing with common backend tasks.

## Run Locally

```sh
# clone this repo
git clone https://github.com/bmilcs/mdn-express-local-library

# change directories
cd mdn-express-local-library

# install dependencies
npm install

# run server
npm run serverstart
```

## Notes

UML association diagram:

- shows models we define in boxes
- shows relationships between models
- shows **multiplicities**: min & max numbers of each model that may be present in the relationship

For example:

- Lines connecting `Book` & `Genre`: shows that they're connected
- Numbers close to `Book`: show a `Genre` must have 0 or more `Books` (as many as you'd like)
- Numbers close to `Genre`: show a `Book` can have zero or more associated genres

![UML Association Diagram](screenshots/library_website_-_mongoose_express.png)

Model View Controller in Express

![Express MVC](screenshots/mvc_express.png)

Form Handling Process

![Form Handling](screenshots/web_server_form_handling.png)
