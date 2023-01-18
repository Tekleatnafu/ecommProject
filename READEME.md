React Tutorial - Build ECommerce in 6 Hours [2022]
Welcome to my React and Node tutorial to build a fully-functional e-commerce website exactly like amazon. Open your code editor and follow me for the next hours to build an e-commerce website using MERN stack (MongoDB, ExpressJS, React and Node.JS).

Watch it on Youtube: https://www.youtube.com/watch?v=CDtPMR5y0QU

Demo Website
👉 Render : https://amazona.onrender.com
You Will Learn
HTML5 and CSS3: Semantic Elements, CSS Grid, Flexbox
React: Components, Props, Events, Hooks, Router, Axios
Context API: Store, Reducers, Actions
Node & Express: Web API, Body Parser, File Upload, JWT
MongoDB: Mongoose, Aggregation
Development: ESLint, Babel, Git, Github,
Deployment: Heroku
Run Locally

1. Clone repo
   $ git clone git@github.com:basir/mern-amazona.git
   $ cd mern-amazona
2. Create .env File
   duplicate .env.example in backend folder and rename it to .env
3. Setup MongoDB
   Local MongoDB
   Install it from here
   In .env file update MONGODB_URI=mongodb://localhost/amazona
   OR Atlas Cloud MongoDB
   Create database at https://cloud.mongodb.com
   In .env file update MONGODB_URI=mongodb+srv://your-db-connection
4. Run Backend
   $ cd backend
   $ npm install
   $ npm start
5. Run Frontend

# open new terminal

    $ cd frontend
    $ npm install
    $ npm start 6. Seed Users and Products
    Run this on browser: http://localhost:5000/api/seed
    It returns admin email and password and 6 sample products 7. Admin Login
    Run http://localhost:3000/signin
    Enter admin email and password and click signin
    Support
    Contact Instructor: Basir

# Lessons

    1. Introduction
    2. Install Tools
    3. Create React App
    4. Create Git Repository
    5. List Products
        i. create products array
        ii. add product images
        iii. render products
        iv. style products
    6. Add page routing

        i. npm i react-router-dom
        ii. create route for home screen
        iii. create router for product screen
    7. Create Node.JS Server
        i. run npm init in root folder
        ii. Update package.json set type: module
        iii. Add .js to imports
        iv. npm install express
        v. create server.js
        vi. add start command as node backend/server.js
        vii. require express
        viii. create route for / return backend is ready.
        ix. move products.js from frontend to backend
        x. create route for /api/products
        xi. return products
        xii. run npm start

    8. Fetch Products From Backend
        i. set proxy in package.json
        ii. npm install axios
        iii. use state hook
        iv. use effect hook
        v. use reducer hook

    9. Manage State By Reducer Hook
        i. define reducer
        ii. update fetch data
        iii. get state from usReducer

    10. Add bootstrap UI Framework
        i. npm install react-bootstrap bootstrap
        ii. update App.js

    11. Create Product and Rating Component
        i. create Rating component
        ii. Create Product component
        iii. Use Rating component in Product component
    12. Create Product Details Screen
        i. fetch product from backend
        ii. create 3 columns for image, info and action

    13. Create Loading and Message Component
        i. create loading component
        ii. use spinner component
        iii. craete message component
        iv. create utils.js to define getError fuction

    14. Create React Context For Add Item To Cart
        i. Create React Context
        ii. define reducer
        iii. create store provider
        iv. implement add to cart button click handler

    15. Complete Add To Cart
        i. check exist item in the cart
        i. check count in stock in backend

    16. Create Cart Screen
        i. create 2 columns
        ii. display items list
        iii. create action column

    17. Complete Cart Screen
        i. click handler for inc/dec item
        ii. click handler for remove item
        iii. click handler for checkout

    18. Create Signin Screen
        i. create sign in form
        ii. add email and password
        iii. add signin button

    19. Connect To MongoDB Database
        i. create atlas monogodb database
        ii. install local mongodb database
        iii. npm install mongoose
        iv. connect to mongodb database

    20. Seed Sample Products
        i. create Product model
        ii. create seed route
        iii. use route in server.js
        iv. seed sample product
        v. Seed Sample Users

create user model
seed sample users
Create Signin Backend API
create signin api
npm install jsonwebtoken
define generateToken
Complete Signin Screen
handle submit action
save token in store and local storage
show user name in header
Create Shipping Screen
create form inputs
handle save shipping address
add checkout wizard bar
Create Sign Up Screen
create input forms
handle submit
create backend api
Implement Select Payment Method Screen
create input forms
handle submit
Create Place Order Screen
show cart items, payment and address
calculate order summary
Implement Place Order Action
handle place order action
create order create api
Create Order Screen
create backend api for order/:id
fetch order api in frontend
show order information in 2 cloumns
Pay Order By PayPal
generate paypal client id
create api to return client id
install react-paypal-js
use PayPalScriptProvider in index.js
use usePayPalScriptReducer in Order Screen
implement loadPaypalScript function
render paypal button
implement onApprove payment function
create pay order api in backend
Display Order History
create order screen
create order history api
use api in the frontend
Create Profile Screen
get user info from context
show user information
create user update api
update user info
Publish To Heroku
create and config node project
serve build folder in frontend folder
Create heroku account
connect it to github
Create mongodb atlas database
Set database connection in heroku env variables
Commit and push
Add Sidebar and Search Box
add sidebar
add search box
Create Search Screen
show filters
create api for searching products
display results
Create Admin Menu
define protected route component
define admin route component
add menu for admin in header
Create Dashboard Screen
create dashboard ui
implement backend api
connect ui to backend
Manage Products
create products list ui
implement backend api
fetch data
Create Product
create products button
implement backend api
handle on click
Create Edit Product
create edit button
create edit product ui
dispaly product info in the input boxes
Implement Update Product
create edit product backend api
handle update click
Upload Product Image
create cloudinary account
use the api key in env file
handle upload file
implement backend api to upload
Delete Product
show delete button
implement backend api
handle on click
List Orders
create order list screen
implement backen api
fetch and display orders
Deliver Order
add deliver button
handle click action
implement backen api for deliver
Delete Order
add delete button
handle click action
implement backen api for delete
List Users
create user list screen
implement backen api
fetch and display users
Edit User
create edit button
create edit product ui
dispaly product info in the input boxes
implement backend api
handle edit click
Delete User
add delete button
handle click action
implement backen api for delete
Choose Address On Google Map
create google map credentials
update .env file with Google Api Key
create api to send google api to frontend
create map screen
fetch google api
getUserLocation
install @react-google-maps/api
use it in shipping screen
apply map to the checkout screen
Email order receipt by mailgun
create mailgun account
add and verify your domain to mailgun
install mailgun-js
set api key in env file
change pay order in orderRouter
send email order receipt
Review Products
create submit review form
handle submit
implement backend api for review
Upload multiple Images
add images to product model
get images in edit screen
show images in product screen
Upgrade To React 18
install node-check-updates
ncu -u
remove package-lock.json
npm install
replace render with createRoot
fix LinkContainer error
