# Front End Capstone 

Using React.js developed front end implementation for a minimalistic single page ecommerce web app.

Gives the user the ability to select different styles, view related products, and check reviews and ratings for the selected product.

# Overview

The overview component enables users to look through different styles, examine images of both the product and its styles, and pick the size and quantity of the product they want to add to their shopping cart.

![overview](https://user-images.githubusercontent.com/24445744/218268059-d9c008a2-3db2-469a-a64a-6c8d7be2271b.gif)

# Related Items & Comparison
The related products component allows users to explore related items and conpare them to the item currently selected.

![related](https://user-images.githubusercontent.com/24445744/218268070-c3bf9a08-327d-4110-bb34-f46c6d19f602.gif)

# Questions & Answers
The questions component allows users to see existing questions and answers about a certain product (giving them an option to mark it as helpful). It also allows users to view photos associated with answers and search of questions using the search bar.

![questions](https://user-images.githubusercontent.com/24445744/218268066-7d7efab1-f44b-469a-b93e-dfdffbd910b6.gif)

# Ratings & Reviews
The ratings component allows users to see a specific product's rating, sort reviews based on various metrics, filter them based on their rating value, and write their own review.
![ratings](https://user-images.githubusercontent.com/24445744/218268068-7c07ebb3-a340-4a94-92ee-389a76026065.gif)


# Installation  

Installation instructions

Clone the repository.

git clone https://github.com/robin1004/front-end-capstone.git

To access data from the API, you must create a GitHub API Token (https://github.com/settings/tokens), create a .env file, and insert that token into the .env file along with a port number (port number can be of your choosing).

```
PORT=1100

AUTHTOKEN=AUTH_TOKEN_GOES_HERE
```

Install NPM packages that require to run the application.

`npm install`

Compile the webpack.

`npm run build`

Start the server.

`npm server`

Open the web browser and enter localhost:1100
