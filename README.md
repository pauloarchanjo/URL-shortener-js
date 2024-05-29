# URL Shortener JS

A simple and efficient URL shortener using EJS, Node.js, and Mongoose.

![Screenshot](frontpage.png)

## Technologies Used

- **Node.js**: JavaScript platform for server-side development.
- **EJS (Embedded JavaScript Templating)**: Templating engine to render dynamic pages.
- **Mongoose**: MongoDB object modeling tool designed to work in an asynchronous environment.

## Features

- **Shorten URLs**: Converts long URLs into short, shareable URLs.
- **Redirection**: Automatically redirects users to the original URL when accessing the short URL.
- **URL Management**: Allows viewing and managing shortened URLs.

## Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/url-shortener-js.git
    ```
2. Navigate to the project directory:
    ```bash
    cd url-shortener-js
    ```
3. Install the dependencies:
    ```bash
    npm install
    ```
4. Configure the `.env` file with your MongoDB credentials:
    ```env
    MONGODB_URI=your_mongodb_uri
    ```
5. Start the server:
    ```bash
    npm start
    ```

## How to Use

1. Go to `http://localhost:3000` in your browser.
2. Enter the URL you want to shorten and click the "Shorten" button.
3. Use the generated short URL to share with others.

## Contribution

Contributions are welcome! Feel free to open issues and pull requests.

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
