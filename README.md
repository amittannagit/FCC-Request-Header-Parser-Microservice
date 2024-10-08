# Request Header Parser Microservice

This is a Request Header Parser Microservice project built as part of the [freeCodeCamp Back End Development and APIs Certification](https://www.freecodecamp.org/learn/back-end-development-and-apis/back-end-development-and-apis-projects/request-header-parser-microservice).

## Project Overview

The Request Header Parser Microservice API extracts and returns information from the request headers. The API provides details such as the user's IP address, preferred language, and software (user agent).

### Features

- **IP Address**: Returns the IP address of the client making the request.
- **Language**: Returns the preferred languages from the `Accept-Language` header.
- **Software**: Returns the user agent string from the `User-Agent` header.

## API Endpoints

### GET `/api/whoami`

- **Response**:
  ```json
  {
    "ipaddress": "127.0.0.1",
    "language": "en-US,en;q=0.9",
    "software": "Mozilla/5.0 (Windows NT 10.0; Win64; x64) AppleWebKit/537.36 (KHTML, like Gecko) Chrome/92.0.4515.107 Safari/537.36"
  }
  ```

### Examples

- `/api/whoami` returns the client's IP address, preferred language, and user agent string.

## Getting Started

### Prerequisites

- [Node.js](https://nodejs.org/) installed on your machine.

### Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/amittannagit/FCC-Request-Header-Parser-Microservice.git
   ```
2. **Navigate to the project directory**:
   ```bash
   cd FCC-Request-Header-Parser-Microservice
   ```
3. **Install the dependencies**:
   ```bash
   npm install
   ```
4. **Start the server**:
   ```bash
   npm start
   ```

### Running the API Locally

Once the server is running, you can access the API by navigating to `http://localhost:3000/api/whoami` in your web browser or using tools like `curl` or Postman.

## Deployment

You can deploy this project to platforms such as [Heroku](https://www.heroku.com/), [Vercel](https://vercel.com/), or [Replit](https://replit.com/).

## License

This project is open source and available under the [MIT License](LICENSE).

## Acknowledgments

- Thanks to [freeCodeCamp](https://www.freecodecamp.org/) for providing the project guidelines.
