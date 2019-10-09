# react-router-app

> ### Router react project  (User Navigation). In this this project user can navigate from one page to another with utmost efficiency. Pages available are home page, user dashboard, notFound incase user navigate to a page that does not exist, posts, products and productDetails.

## Getting started


To get this project running locally:

- Clone this repo `https://github.com/Terahpatrick/react-router-app.git`
- `npm install` or `yarn add` to install all req'd dependencies
- `npm start` or `yarn start` to start the local server (this project uses create-react-app)

Local web server will use port 3000. You can configure port in scripts section of `package.json`: we use [cross-env](https://github.com/kentcdodds/cross-env) to set environment variable PORT for React scripts, this is Windows-compatible way of setting environment variables.
 
Alternatively, you can add `.env` file in the root folder of project to set environment variables (use PORT to change webserver's port). This file will be ignored by git, so it is suitable for API keys and other sensitive stuff. Refer to [dotenv](https://github.com/motdotla/dotenv) and [React](https://github.com/facebookincubator/create-react-app/blob/master/packages/react-scripts/template/README.md#adding-development-environment-variables-in-env) documentation for more details. Also, please remove setting variable via script section of `package.json` - `dotenv` never override variables if they are already set.  

### Making requests to the backend API

They is no backend for this project.

## Functionality overview

The example application is a simple navigation for users.


**The general page breakdown looks like this:**

- Home page (URL: /#/ )
    - Navigation

- Products page (URL: /#/products )
    - display a list of products

- Product Details page (URL: /#/products/:id )
    - display details of a product

- Posts page (URL: /#/posts )
    - Display list of posts
  
- Admin Dashboard page (URL: /#/admin )
    - Admin Dashboard

- notFound page (URL: /#/notFound )
    - For pages that does not exist.


