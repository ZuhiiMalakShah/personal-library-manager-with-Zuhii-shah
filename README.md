# Personal Library Manager

## Overview
The **Personal Library Manager** is a Streamlit-based web application designed to help you organize, track, and gain insights into your personal book collection. This application features an intuitive and responsive user interface, allowing you to add, search, filter, and manage your books seamlessly.

## Features

### 1. Library Management
- **Add Books:** Add books with details such as title, author, year, genre, and read status.
- **View Library:** Browse your book collection with filtering and sorting options:
  - Filter by status (All, Read, Unread).
  - Filter by genre.
  - Sort by Title, Author, Year, or Date Added.
- **Mark as Read/Unread:** Toggle the read status of books.
- **Remove Books:** Remove unwanted books from your library.

### 2. Search Functionality
- Search for books using specific criteria:
  - Title
  - Author
  - Year
  - Genre
- Displays search results dynamically.

### 3. Insights
- Gain valuable insights into your reading habits:
  - Total number of books.
  - Number of books read.
  - Percentage completion of your reading goals.

### 4. Responsive UI/UX
- Beautiful, gradient-based card designs for books.
- Fully responsive tabs and layout for seamless navigation.
- Dynamic feedback on actions like adding or removing books.

## Installation and Setup

### Prerequisites
- Python 
- Streamlit library

### Installation
1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd personal-library-manager
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Run the application:
   ```bash
   streamlit run app.py
   ```

4. Open your browser and navigate to the displayed local URL (e.g., `http://localhost:8501`).

## File Structure
```
personal-library-manager/
|
|-- app.py                  # Main application file
|-- zuhi.json            # Data storage file for the library
|-- requirements.txt        # Dependencies for the project
```

## Usage Instructions

### Adding a Book
1. Navigate to the "+ Add Book" tab.
2. Fill in the book details (Title, Author, Year, Genre, Read Status).
3. Click **Add to library** to save the book.

### Managing Books
1. Navigate to the "Library" tab.
2. Use the filters and sorting options to view your collection.
3. Use the action buttons to toggle read status or remove books.

### Searching for Books
1. Navigate to the "Search" tab.
2. Enter a search term and select a criterion (e.g., Title, Author).
3. View the results dynamically.

### Viewing Insights
1. Navigate to the "Insights" tab.
2. View statistics such as total books, books read, and completion percentage.

## Customization
The application can be customized by editing the following sections:
- **Genres:** Modify the `genre` options in the "Add Book" tab.
- **Styling:** Update the CSS under `st.markdown` to change the theme and layout.
- **Storage:** Modify the `library.json` file structure for alternative storage formats.

## Key Components
- **Frontend:**
  - Styled using custom CSS for an intuitive and modern look.
  - Responsive design for various screen sizes.
- **Backend:**
  - Data handling with Python's `json` module.
  - Functions for adding, removing, searching, and toggling book statuses.

## Future Enhancements
- Implement user authentication for multi-user support.
- Add cloud storage options for better accessibility.
- Include export/import functionality for the library.
- Integrate graphs to visualize reading trends over time.

## Credits
- Developed by **[Zuhi shah ](https://github.com/ZuhiiMalakShah)**.
- Built with ❤️ using Streamlit.

## License
This project is licensed under the MIT License. Feel free to use, modify, and distribute the application as needed.

