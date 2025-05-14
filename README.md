 Developed a feature-rich Q&A platform similar to Stack Overflow using the MERN stack (MongoDB, Express.js, React.js, Node.js)
* Developed a responsive platform accross all devices including mobiles & tablets.
* Implemented secure user authentication and authorization with sign-up, login, password management, and JWT-based tokens.
* Enabled extensive user interaction with question asking, editing, deletion, voting, answering, and profile management.
* Integrated Stripe for secure payment processing for different subscription.
* Integrated an AI chatbot for interactive learning and engagement, with email verification for secure access.
* Enhanced user experience with dynamic theme personalization (day/night mode, auto-theme based on time/weather).
* Leveraged Node.js, Express.js, Bcrypt.js, and other technologies for a robust and scalable backend foundation.
* Employed Redux Toolkit for efficient state management and data flow.
* Incorporated Axios for simplified API communication.

## Technologies
* MERN stack
* React JS
* Redux Toolkit, React Router,Axios.
* Node JS., Express JS.
* Bcrypt js, Json Web Token (JWT).
* Stripe Payment.
* Geolocation , weather api , Open AI
	
## Setup
1. Set up environment variables:
   - Create a `.env` file in the `client` directory.
   - Add the following variables to the `.env` file, replacing the placeholder values with your actual credentials:
     ```
     REACT_APP_SHARE_URL="Your Website URL" (optional, default value "http://localhost:3000")
     REACT_APP_URL="your backend URL" (default value "http://localhost:4000")
     REACT_APP_API_KEY="Open weather API key"
     REACT_APP_STRIPE_PUBLISHABLE_KEY="Your stripe publishable key"
     ```

   - Create a `.env` file in the `server` directory.
   - Add the following variables to the `.env` file, replacing the placeholder values with your actual credentials:
     ```
     PORT="port number on which you want to run" (default value "4000")
     MONGODB_URI="your_mongo_uri"
     JWT_SECRET="your_secret_key"
     SMTP_HOST="smtp.gmail.com"
     SMTP_PORT=587
     SMTP_MAIL="your email"
     SMTP_PASSWORD= "your email app key"
     OPEN_AI_KEY= "your open AI key"
     STRIPE_SECRET_KEY="your Stripe secret Key"
     ```
2. Install dependencies and run server:
#### Frontend
```
 cd ../client
 npm install
 npm start
```
#### Backend
```
cd ../server
npm install
npm start
```
