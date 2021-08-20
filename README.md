# project3-planning# Project-Name ⏱️

## Description

Have you ever wanted ice cream delivered straight to your door, but found yourself lacking useful product information because popular delivery services don't offer it?
Well with Frizzy - the specialized frozen dessert delivery service, any and all useful information pertaining to our ice cream products will be available to you on our app.
The goal is to provide a seamless experience for ordering your desserts, while giving you all the allergy and nutritional information you want.

### Project Links

- [Back end git](https://project3-icecream.herokuapp.com/icecream/)
- [Front end git](https://confident-shannon-bd54f9.netlify.app/)

### Wireframes and Architecture

- Wireframes: -[All Wireframes](https://wireframepro.mockflow.com/view/Mb3f454b8fa8eb608748b4bb2b52e85e91629472419819#/page/ff033a09a6c940779a8fbe2639fa0c)
- Architecture: [Google Drawing](https://docs.google.com/drawings/d/1pUDtzYKNxLvJLM2DC-nWmWA9VZZ3HOZQLnL0vZU2H9c/edit)

### Time/Priority Matrix

| Component                       | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------------------- | :------: | :------------: | :-----------: | :---------: |
| Git management                  |    H     |      8hrs      |       0       |      0      |
| Q&A and bug fixes               |    H     |     3.5hrs     |       0       |      0      |
| Connection                      |    H     |      1hr       |       0       |      0      |
| Express                         |    H     |      1hr       |       0       |      0      |
| Routes                          |    H     |      2hrs      |       0       |      0      |
| Controllers                     |    H     |      3hrs      |       0       |      0      |
| Seed                            |    H     |      2hrs      |       0       |      0      |
| Deployment                      |    H     |      2hrs      |       0       |      0      |
| Install and set up react router |    H     |     0.5hrs     |       0       |      0      |
| Switch, Links, Routes           |    H     |      2hrs      |       0       |      0      |
| Header                          |    H     |      2hrs      |       0       |      0      |
| Home                            |    H     |      4hrs      |       0       |      0      |
| CRUD options                    |    H     |      6hrs      |       0       |      0      |
| aboutus/aboutuspage             |    H     |      2hrs      |       0       |      0      |
| Menu                            |    H     |      8hrs      |       0       |      0      |
| make your own                   |    H     |      4hrs      |       0       |      0      |
| list of product                 |    H     |      4hrs      |       0       |      0      |
| Styling                         |    H     |      8hrs      |       0       |      0      |
| Responsiveness                  |    H     |      5hrs      |       0       |      0      |
| Product details                 |    L     |      7hrs      |       0       |      0      |
| latest offers                   |    L     |      4hrs      |       0       |      0      |
| Extra Styling                   |    L     |      2hrs      |       0       |      0      |
| My bag/ my bag page             |    L     |      2hrs      |       0       |      0      |
| Total                           |    H     |     83hrs      |       0       |      0      |

## MVP/Post-MVP

### MVP

- Connection
- Models( )
- Set up express server in index.js
- Routes
- Controllers
- Deployment to heroku
- Install and set up “react router” in index and app
- Sweet Header in App outside of Routes that gives option to go back to Home
- Switch Routes in App (Home, Form, Timers)
- Home Page
  - search bar
  - img scroll
  - popular
  - recent
- Color palette/styling
- Menu
  - list of product
  - more
  - latest offers
- list of product
  - img list of products
- product details
- latest offers
  - img list of latest offers
  - Check Offers
- more
  - My bag/ my bag page
  - shopping cart/checkout
  - notification
  - Inbox
  - aboutus/aboutuspage
- make your own
  -edit your stuff

### Time/Priority Matrix post mvp

| Component                                  | Priority | Estimated Time | Time Invested | Actual Time |
| ------------------------------------------ | :------: | :------------: | :-----------: | :---------: |
| Create login/sign-in form                  |    H     |      3hrs      |       0       |      0      |
| Connecting login/sign-in form from backend |    H     |     3.5hrs     |       0       |      0      |
| payments/payments page                     |    L     |      3hrs      |       0       |      0      |
| profile                                    |    L     |      4hrs      |       0       |      0      |
| reset passwrod                             |    L     |      4hrs      |       0       |      0      |
| check mobile for login code                |    L     |      8hrs      |       0       |      0      |
| make new password                          |    L     |      4hrs      |       0       |      0      |
| Splash screen                              |    L     |      3hrs      |       0       |      0      |
| Total                                      |    L     |    32.5hrs     |       0       |      0      |

### Post-MVP

- reset passwrod
- check mobile for code
- make new password
- Splash screen
- log in forms
  - logn in page
  - encrypt password
  - forget password
    -login with
- Sign up forms
  - sign up page
  - create user name/password
- payments/payments page - add card
  -menu - profile

## Components - Descriptions

- LogoHeader: renders our logo at the top of each page
- NavBar:
  - mobile: footer that sticks to the bottom of the screen even when you scroll
  - desktop: standard header navbar at top of page
- Dropdown.js - dropdown menu with list of cities that filters the ice cream parlours being rendered
- LatestOffers.js: place for coupons
- Popular.js: an image/link carousel that renders a few options of our choice
- IceCreamList.js: list of ice cream products in our api
- Menu.js: - a page that renders DessertTypes.js
- DessertTypes.js - renders a list of dessert types (ice cream, sorbet, italian ice, etc) that links to each of their respective pages
- ShoppingCart - sets a new state of products that the user intends on buying
- OrderConfirmation.js - renders final confirmation of our ShoppingCart's order function.
- About - a blurb about our team, links to our websites, and a little description of our site and how we built it

## Additional Libraries

- Bootstrap
- Axios
- React, react-router-dom
- Node
- Express
