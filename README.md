<div align="center">

# Books Store

![HTML](https://img.shields.io/badge/HTML-5-E34F26)
![CSS](https://img.shields.io/badge/CSS-3-1572B6)
![JavaScript](https://img.shields.io/badge/JavaScript-ES6-F7DF1E)

</div>

<img width="2560" height="1440" alt="Screenshot 2026-06-14 135551" src="https://github.com/user-attachments/assets/ba3e4a11-4734-4b4f-bf5d-bc4c6523465c" />


## Overview

Books Store is a static website for displaying a small collection of books. The home page shows book cards with cover images, descriptions, and payment buttons.

A simple responsive book store website where users can browse books, open the payment page, and submit card details through a validation form.

The site also includes separate navigation pages for About Us and Contact Us, plus a payment page that validates card details before sending them to an API.

## Features

- Responsive desktop and mobile navigation
- Book listing grid with cover images and descriptions
- Pay buttons for each book
- Payment form with card number, expiry date, and CVV inputs
- Client-side payment validation
- Success page flow after a valid payment response

## Site Concept

The aim of the website is to present books in a simple online store layout and allow users to move from browsing to payment.

Each book card includes the book cover, title, description, and a Pay button. The payment page checks the user's card details and displays a response message before redirecting to the success page.

## User Flow

- Open the home page
- Browse the available books
- Select Pay on a book card
- Enter card details on the payment page
- Submit the form for validation
- View the payment response and success page

## Main Site Pages

| Page | Description |
|---|---|
| Home | Displays the book cards and Pay buttons |
| About Us | Provides the About Us navigation page |
| Contact Us | Provides the Contact Us navigation page |
| Payment | Collects and validates card details |
| Success | Shows the payment success message |

## Technologies Used

- HTML
- CSS
- JavaScript
- Font Awesome

## Installation

Clone the repository:

```bash
git clone https://github.com/SirRmelTheThird/BooksStore.git
```

Open the project folder:

```bash
cd BooksStore
```

## Running the Project

Run the project through a local server because the payment page sends an API request.

### Option 1: VS Code Live Server

Open the project folder in Visual Studio Code, install the Live Server extension, then right-click `BooksStore/index.html` and select `Open with Live Server`.

### Option 2: Python Server

Start a local server from the repository root:

```bash
python -m http.server 8000
```

Open the site in your browser:

```text
http://localhost:8000/BooksStore/index.html
```
