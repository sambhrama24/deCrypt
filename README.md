# deCrypt

[![Build Status](https://travis-ci.org/sambhrama24/deCrypt.svg?branch=master)](https://travis-ci.org/sambhrama24/deCrypt)
[![License](https://img.shields.io/badge/license-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![GitHub issues](https://img.shields.io/github/issues/sambhrama24/deCrypt.svg)](https://github.com/sambhrama24/deCrypt/issues)
[![GitHub stars](https://img.shields.io/github/stars/sambhrama24/deCrypt.svg)](https://github.com/sambhrama24/deCrypt/stargazers)

## Description

deCrypt is a personalized cryptocurrency collection web app for real-time tracking of favorite coins in INR. It eliminates the need for constant coin searching, providing a streamlined experience for cryptocurrency enthusiasts. The app is built using HTML5, CSS3, JavaScript, EJS, ExpressJS, Binance WebSocket, NPM packages, and MongoDB as the NoSQL database through ROBO 3T.

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgments](#acknowledgments)

## Features

- **Real-time Tracking:** Track your favorite cryptocurrencies in real-time.
- **INR Support:** Prices are displayed in Indian Rupees for user convenience.
- **Personalization:** Customize your collection for a personalized experience.
- **Streamlined UI:** User-friendly interface for easy navigation.
- **Data Storage:** MongoDB is used for efficient and scalable data storage.

## Installation

Follow these steps to set up and run deCrypt on your local machine:

1. Clone the repository:

   ```bash
   git clone https://github.com/sambhrama24/deCrypt.git
   ```

2. Change into the project directory:

   ```bash
   cd deCrypt
   ```

3. Install dependencies:

   ```bash
   npm install
   ```

4. Configure MongoDB:

   - Make sure MongoDB is installed and running.
   - Add your credentials to the env file
   - Update the database configuration in `config/database.js`.

5. Start the application:

   ```bash
   nodemon app.js
   ```

6. Open your browser and go to [http://localhost:3000](http://localhost:3000).

## Usage

1. Sign up for an account or log in if you already have one.
2. Add your favorite cryptocurrencies to your collection.
3. Enjoy real-time tracking and pricing information in INR.

## Contributing

We welcome contributions! To contribute to deCrypt, follow these steps:

1. Fork the repository on GitHub.
2. Clone the forked repository to your local machine.
3. Create a new branch for your feature or bug fix.
4. Make your changes and commit them.
5. Push the changes to your fork on GitHub.
6. Submit a pull request to the main repository.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- **Binance WebSocket:** Used for real-time cryptocurrency data.
- **MongoDB:** NoSQL database for efficient data storage.
- **ExpressJS:** Web application framework for Node.js.

---
