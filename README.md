# Simple Golang Server

This project is a basic server written in Go (Golang) to demonstrate routing, form handling, and serving HTML pages. The server provides the following functionality:

- **Home Page (`/`)**: Displays a home page.
- **Hello Page (`/hello`)**: Displays "Hello" on the page.
- **Form Page (`/form.html`)**: Displays an HTML form where you can enter a username and password. Submitting the form sends the data to the `/form` route, where the submitted credentials are displayed.

## Features

- Simple routing using the `net/http` package.
- Basic HTML form handling.
- Display of user-submitted data on the browser.

## Prerequisites

- Go (Golang) installed on your machine. [Download Go](https://go.dev/dl/)

## How to Run

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_name>
   ```

2. Run the server:
   ```bash
   go run main.go
   ```

3. Open your browser and navigate to the following routes:

   - `http://localhost:8080/` to access the Home Page.
   - `http://localhost:8080/hello` to see the Hello Page.
   - `http://localhost:8080/form.html` to access the Form Page.

4. On the Form Page (`/form.html`):
   - Enter a username and password.
   - Click **Submit**.
   - You will be redirected to `/form`, where your username and password will be displayed as plain text.



Happy coding!
