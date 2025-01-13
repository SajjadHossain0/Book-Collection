# Bookshelf Web Application

A simple bookshelf web application that allows users to add, view, and manage a collection of books with cover images, titles, and author details. The app uses local storage to save the added books, ensuring the data persists across browser sessions.

## Features

- **Add Books**: Add new books with cover images, titles, and author names.
- **Responsive Design**: The layout adapts to different screen sizes.
- **Local Storage**: Saves book data locally to ensure it persists even after refreshing the browser.
- **Interactive Modal**: Add books through a user-friendly modal form.

## Live Demo

You can try the live demo [here](#).

## Screenshots

### Bookshelf View
![Screenshot 2025-01-13 151310](https://github.com/user-attachments/assets/d8f1da6c-dfb2-4846-a759-84f49f4d5564)

### Add New Book Modal
![Screenshot 2025-01-13 151255](https://github.com/user-attachments/assets/0ecd6f93-0f58-489f-b041-491c444f3409)

## Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/SajjadHossain0/Book-Collection.git
   ```
2. Open the `index.html` file in any modern web browser.

## Usage

1. Click on the "Add Book" box to open the modal.
2. Fill in the required details: cover image URL, book title, and author name.
3. Click on "Add Book" to add the book to the bookshelf.
4. The added books will appear as cards on the bookshelf.

## Technologies Used

- **HTML**: For structuring the web application.
- **CSS**: For styling the application and ensuring responsiveness.
- **JavaScript**: For handling functionality like adding books, managing local storage, and updating the UI dynamically.

## How It Works

1. **Adding a Book**: 
   - When a user fills out the modal form and submits it, the book details are saved to `localStorage`.
   - The bookshelf is updated dynamically with a new book card.

2. **Persistent Storage**: 
   - All added books are stored in the browser's `localStorage`. When the page reloads, the stored books are loaded automatically.

3. **Responsive Design**:
   - The application uses CSS Grid to create a responsive layout that adjusts to various screen sizes.

## Future Enhancements

- Add a search feature to find books easily.
- Include an option to delete books from the bookshelf.
- Implement categories or tags for books.

## Contributing

Contributions are welcome! Please feel free to fork this repository and submit a pull request with your improvements.

## Author

**Md. Sajjad Hossain**  
[GitHub](https://github.com/sajjadhossain0) | [Portfolio](https://sajjadhossain.onrender.com)
