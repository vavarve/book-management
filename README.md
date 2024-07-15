# Book Management Application

This is a simple Angular application for managing a list of books using NgRx for state management.

## Features

- Add a new book to the list.
- Remove a book from the list.
- View the list of books.
- State management using NgRx.
- Side effects handling with NgRx Effects.

## Installation

1. **Clone the repository**:
   git clone https://github.com/your-username/book-management.git
   cd book-management

2. **Install dependencies**:
   npm install

3. **Run the application**:
   ng serve

   The application will be available at `http://localhost:4200/`.

## Usage

### Adding a Book

1. Enter the book ID, title, and author in the input fields.
2. Click the "Add Book" button to add the book to the list.

### Removing a Book

1. Click the "Remove Book" button next to the book you want to remove.

## Project Structure

```plaintext
src/
├── app/
│   ├── books/
│   │   ├── book.actions.ts
│   │   ├── book.effects.ts
│   │   ├── book.reducer.ts
│   │   ├── book.service.ts
│   ├── book-list/
│   │   ├── book-list.component.css
│   │   ├── book-list.component.html
│   │   ├── book-list.component.ts
│   ├── models/
│   │   ├── book.ts
│   ├── app-routing.module.ts
│   ├── app.component.css
│   ├── app.component.html
│   ├── app.component.ts
│   ├── app.module.ts
│   ├── app.state.ts
└── assets/
└── environments/
└── styles.css
```
