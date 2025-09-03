# Book-Finder---The-college-student
A clean, responsive web app that helps students quickly find books using the Open Library API. Search by title, author, or subject with an intuitive interface designed for academic use.
About the Project
Book Finder is designed specifically for students who need an efficient way to search for academic and leisure reading materials. The application provides a clean, intuitive interface with quick search options and detailed book information.

How to Run Locally
Download the project files

Open index.html in your web browser, or

For best results, use a local server:

bash
# Python
python -m http.server 8000

# Node.js (if you have http-server installed)
npx http-server

# PHP
php -S localhost:8000
Visit http://localhost:8000 in your browser

Tech Stack
HTML5: Page structure and content

TailwindCSS: Styling and responsive design

JavaScript: Functionality and API calls

Open Library API: Book data source

Font Awesome: Icons

Features
Search by title, author, or subject

Quick-search buttons for popular topics

Responsive design for all devices

Book covers and details display

Loading indicators and error handling

Clean, student-friendly interface

API Usage
Uses the Open Library Search API:

Endpoint: https://openlibrary.org/search.json?title={query}

Returns book data with titles, authors, years, and cover images

Browser Compatibility
Works on all modern browsers including Chrome, Firefox, Safari, and Edge.

Perfect for students needing fast access to book information for their studies!


