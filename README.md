# Book Manager

## Project Overview

The Book Manager is a Python project that allows users to manage book collections and publisher information. It includes features for adding, editing, deleting, and searching books based on various criteria.

### Features:

- **Add a new publisher**
  - Information: Name, phone number, city

- **Add a new book**
  - Information: ISBN, title, year, publisher, previous edition, price

- **Edit an existing book**

- **Delete a book**

- **Search books based on criteria:**
  - All books
  - Based on title (zero or more books shall be returned)
  - Based on ISBN (one or zero book shall be returned)
  - Based on publisher (zero or more shall be returned)
  - Based on price range (min and max) (zero or more shall be returned)
  - Based on year (zero or more shall be returned)
  - Based on title and publisher (zero or more shall be returned)

## Installation Instructions

To run this project, you need to have the following software installed:

- GitHub
- Docker
- MongoDB
- Python 3

### Steps:

1. **Clone the Repository:**

   ```sh
   git clone https://github.com/your-username/book-manager-Mongodb.git
   cd book-manager-Mongodb
   ```

2. **Set up MongoDB Database:**

   - Ensure MongoDB is running on your system.
   - Update the database configuration in the project settings.

3. **Build and Run Docker Containers:**

   - Ensure Docker is running on your system.
   - Build the Docker image:

     ```sh
     docker build -t book-manager .
     ```

   - Run the Docker container:

     ```sh
     docker run -d -p 8000:8000 book-manager
     ```

4. **Install Python Dependencies:**

   ```sh
   pip install -r requirements.txt
   ```


5. **Start the Application:**

   ```sh
   python manage.py runserver
   ```
