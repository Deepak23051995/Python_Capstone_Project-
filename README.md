# Python_Capstone_Project-
Book Scraper and Filter Application

Description:

The Book Scraper and Filter Application is a Python-based tool designed to fetch book data from the Open Library API. The application allows users to search for books, filter them based on various criteria (such as genre, rating, year of publication, and rank), and provide random book suggestions from the filtered list. It also includes the ability to save the filtered book data into CSV and JSON files.

The application features an interactive GUI built using Tkinter, allowing users to easily input their search terms and filter criteria. It can be particularly useful for book enthusiasts, researchers, or anyone looking to organize and explore books from a particular library of works.

Purpose:

The purpose of this project is to provide a simple and intuitive interface for users to:

Search for books based on a specific query.

Apply multiple filters (genre, rating, year, rank) to narrow down search results.

Get random book suggestions from the filtered list.

Save the filtered book data into CSV or JSON format for future reference.

This tool can be useful for book lovers, researchers, educators, or anyone who needs an organized way to browse and filter books based on specific criteria.

Functionalities
1. Search Books:
The user can enter a search term (e.g., book title, author, subject) to find books from the Open Library.

The application fetches data from the Open Library API and displays the available books.

2. Filter Books:
The user can apply filters to narrow down the book list:

Genre: Filter by genre or subject (optional).

Minimum Rating: Filter books by a minimum rating (optional).

Maximum Publication Year: Filter books by the publication year (optional).

Minimum Rank: Filter books by minimum rank (optional).

3. Random Book Suggestion:
After filtering, the user can request a random book suggestion from the filtered list.

A single book is randomly selected and displayed.

4. Save Book Data:
After filtering or fetching the books, the user has the option to save the data in CSV or JSON format.

The saved file contains details such as the book title, author, genre, publication year, rating, and rank.

5. User Interface:
The user interface is designed using Tkinter, providing a simple and clean graphical interface to interact with the program.

The application contains text boxes for entering search queries and filters, and buttons for fetching, filtering, suggesting, and saving books.

Software and Libraries Used
1. Python 3.x:
The programming language used to build the application.

2. Tkinter:
A standard GUI library in Python, used to create the graphical interface for user input and display.

3. Requests:
A simple HTTP library used to make requests to the Open Library API and fetch book data in JSON format.

4. Pandas:
Used for handling and processing the fetched data into a structured format (DataFrame).

Pandas helps to filter, clean, and save the data to CSV/JSON files.

5. Open Library API:
The source of book data. It provides details about books such as title, author, genre, publication year, and rating.

6. JSON:
Used for saving the book data in JSON format, allowing for easy data interchange.

7. CSV:
Used for saving the book data in CSV format, making it easy to open in spreadsheet applications like Microsoft Excel or Google Sheets.

How to Use
Clone the repository or download the project files to your local machine.

Install Required Libraries:

Install the required libraries using pip:

pip install requests pandas

Run the Application:

Open a terminal/command prompt, navigate to the project directory, and run the following command:


python book_scraper_gui.py

Using the GUI:

Upon launching the application, the user will be prompted to:

Enter a search term (e.g., book title, author, or subject).

Optionally apply filters for genre, rating, publication year, and rank.

Click the "Fetch and Filter Books" button to get the results.

Optionally request a random book suggestion from the filtered list.

Save the filtered data to CSV or JSON by clicking the save button.

Exit the Application:

Close the Tkinter window to exit the program.