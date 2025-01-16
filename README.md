# Feeds App

This project is a feeds app that allows users to explore and interact with various media content. It utilizes modern web technologies and libraries to provide a seamless user experience. The app includes features such as searching for media content, adding favorites, and displaying popular movies based on user preferences.

## Table of Contents

- [Project Live Demo](#Project-Live-Demo)
- [Features](#features)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
  
## Project Live Demo
https://lit-cove-88468-0beb0a424a06.herokuapp.com/

![FeedsApp Demo](https://github.com/mianmiantea2019/Feeds-App/blob/master/image/app_demo_v2.gif)

  
## 1. Swagger UI demo for a simple User Registration using Swagger JSON

![Swagger Demo](https://github.com/mianmiantea2019/Feeds-App/blob/master/image/swagger_demo.gif)


## 2. Real-Time Movie Ranking Updates with Two Users

![Ranking Demo](https://github.com/mianmiantea2019/Feeds-App/blob/master/image/ranking_demo.gif)

## Features

- Browse and view a feed of content items.
- Search for specific content items using text-based search.
- Real-time updates for new content using WebSocket communication.

## Technologies Used

### Frontend

- React for building user interfaces.
- Material-UI (MUI) for a consistent and attractive UI design.
- Swiper for a sleek and responsive content carousel.
- Axios for making API requests.
- React-redux for state management.
- React-highlight-words for highlighting search results.

### Backend

- Express.js for building the backend server.
- MongoDB with mongoose for database interactions.
- JSON Web Tokens (jsonwebtoken) for user authentication.
- Redis for caching and improving performance.
- Socket.io for real-time communication.
- Express-rate-limit and express-slow-down for rate limiting and slowing down requests.

## Getting Started

To run the Feeds App on your local machine, follow these steps:

1. Clone the repository: `git clone https://github.com/mianmiantea2019/feeds-app.git`
2. Navigate to the frontend directory: `cd feeds-app/frontend`
3. Build frontend project: `yarn run build`
4. Install backend dependencies: `yarn install`
5. Start the backend server: `yarn start`

The app should now be accessible at http://localhost:5000.

## Usage

- Browse the feed by scrolling through the content items.
- Use the search bar to search for specific content.
- Click on a content item to view more details.
- Mark content items as favorites by clicking the "Favorite" button.
- Real-time updates will notify the updates on user favoriate movie session.

## Contributing

Contributions to the Feeds App are welcome! If you find a bug or want to add a new feature, please follow these steps:

1. Fork the repository.
2. Create a new branch for your feature: `git checkout -b feature-name`
3. Make your changes and commit them: `git commit -m "Add new feature"`
4. Push to your fork: `git push origin feature-name`
5. Create a pull request to the main repository.

## License

This project is licensed under the [MIT License](LICENSE).
