# sublet_app

## Introduction
sublet_app is a web application designed to facilitate the process of subletting properties. It allows users to post sublet listings, search for available sublets, and connect with potential subletters.

## Features
- User authentication: Users can create an account, log in, and manage their profile.
- Create listings: Users can create detailed listings for their sublets, including information such as location, rental price, duration, and additional amenities.
- Search listings: Users can search for available sublets based on various criteria, such as location, price range, and duration.
- Messaging system: Users can communicate with potential subletters through an integrated messaging system.
- Favorite listings: Users can save their favorite listings for future reference.
- Review system: Users can leave reviews and ratings for landlords and subletters based on their experiences.

## Technologies Used
- **Backend**: [Express.js](https://expressjs.com/) - a minimal and flexible Node.js web application framework.
- **Frontend**: [React](https://reactjs.org/) - a JavaScript library for building user interfaces.
- **Database**: [MongoDB](https://www.mongodb.com/) - a document-oriented NoSQL database.
- **Authentication**: [Passport.js](http://www.passportjs.org/) - a popular authentication middleware for Node.js.
- **Messaging**: [Socket.IO](https://socket.io/) - a library for real-time bidirectional event-based communication.
- **Styling**: [CSS](https://developer.mozilla.org/en-US/docs/Web/CSS) - Cascading Style Sheets for styling the application.

## Installation
1. Clone the repository: `git clone https://github.com/Sushiali/sublet_app.git`
2. Install the dependencies:
   - Navigate to the project directory: `cd sublet_app`
   - Install backend dependencies: `npm install`
   - Navigate to the client directory: `cd client`
   - Install frontend dependencies: `npm install`
3. Configure the environment variables:
   - Create a `.env` file in the project root directory.
   - Define the necessary environment variables in the `.env` file (e.g., database connection string, API keys).
4. Start the application:
   - In the project root directory, run `npm run dev` to start both the server and client concurrently.
   - Alternatively, you can run the backend and frontend separately by using `npm run server` and `npm run client` commands.

## Contribution
Contributions to the sublet_app project are welcome! If you find any issues or want to add new features, feel free to open an issue or submit a pull request.

Before contributing, please read the [Contribution Guidelines](CONTRIBUTING.md) for detailed instructions on how to contribute to this project.

## License
This project is licensed under the [MIT License](LICENSE).
