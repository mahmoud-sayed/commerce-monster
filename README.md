# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.\
You will also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can’t go back!**

If you aren’t satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you’re on your own.

You don’t have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn’t feel obligated to use this feature. However we understand that this tool wouldn’t be useful if you couldn’t customize it when you are ready for it.

## Pages Naming and access permissions (website structure)

### Pages

    1- Admin
        - this is our client dashboard to manage his website like (add new product, manage integrate payment Methods like ['apple pay', 'STC'], check his products rate, measure the selling rates).

    2- COMO_Management - this is the owner Main page for next reasons...
        - add new website Design
        - add new customer to Our product as E-Commerce website owner
        -

    3- Landing
        - this landing is mainly for show of our products and our plans, manly used ofr describing our product.

    4- Website
        - this is the e-commerce website we are selling ( this page should be replaceable with other website designs ).

### Sections

    1- Owner Page (COMO_Management) :- will be able to to next...
        - (Add/Remove) Customers
        - Add New website Design
        - Add new promotion and Offers
        - see which Customer was Active and how long time he was active like (1 houre,8 houers)
        - see the selling rate for each Website

    2- Admin Page ( Admin )
        - Will contain many pages like ( charts page that measuring the selling and SEO and website activity for the USER )
          > this will be the first Main page when the User Login to his account He will face this page

        - will contain top navbar and left side nav par
            - top navbar will contain [
                - logo in the left,
                - current customer active inside his store in the middle,
                - how many product his Store sill till now in the middle,
                - user Icon i the left >> on Click on it will show logout Account settings,
                - notification Icon showing the current sold product with full description
                ]

        - page of total product exit in Our user store [
            - each product will be showing as Cards this cards will show the
        ]
