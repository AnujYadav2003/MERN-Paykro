
## Build a basic version of PayTM

Welcome to the Paytm App, a simple application for handling transactions and money transfers. This app provides basic functionality to send money, check balances, and manage user accounts.

## Features

- **User Authentication:** Securely log in with your account to access the Paytm App features.
- **Send Money:** Easily send money to other users within the Paytm network.
- **Check Balance:** View your account balance to keep track of your funds.
- **Seach Other Users:** User can search other users hwo have an account on the App.
- **DecimalData Managment:** Managed decimal balance in backend by using multiple of 100. 

## Technologies Used

- **Frontend:**
  - React: A JavaScript library for building user interfaces.
  - Tailwind CSS: A utility-first CSS framework for styling.

- **Backend:**
  - Node.js: A JavaScript runtime for building server-side applications.
  - Express: A web application framework for Node.js.
  - MongoDB: A NoSQL database for storing user and transaction data.
  - Mongoose: An ODM for manuplating MongoDB.

- **State Managment**
    - UseState: UseState is seamlessly integrated into the React components of the Paytm App. 
    This allows you to manage and update state in functional components, enabling you to create dynamic and interactive user interfaces in your React applications.

    - UseEffect: UseEffect allows you to perform side effects in your functional components.
    It is used for side effects in functional components, such as data fetching, subscriptions, or manually changing the DOM. 

- **Input Validation**
    - (https://github.com/colinhacks/zod) is used for input validation to ensure that user-provided data adheres to the expected schema. This helps prevent invalid or malicious data from compromising the application's integrity. Key Zod schemas include:
        - `signupSchema`: Validates user data during the registration process.
        - `signinSchema`: Validates user credentials during the login process.

- **JWT Authantication**
    - The Paytm App leverages Zod for input validation and JSON Web Tokens (JWT) for secure and efficient user authentication.
