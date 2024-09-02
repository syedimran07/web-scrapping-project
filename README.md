# Web Scrapping Project
This is a Flask application that scrapes product reviews from Flipkart based on user input and stores the data in MongoDB. The scraped reviews are then displayed on a web interface.

## Tech Stack
- Python 3.x
- Flask
- MongoDB
- BeautifulSoup (bs4)
- Requests
- Flask-CORS

  
## Environment Variables
Create a .env file in the project directory and add the following variables:

- MONGO_URI=<your_mongodb_connection_string>
Replace <your_mongodb_connection_string> with your actual MongoDB connection URI.


## Install Dependencies
Run the following command to install the necessary dependencies:

- pip install -r requirements.txt


## API Base URL
The API is configured to run on: http://127.0.0.1:8000

Available Endpoints:

- GET /: Displays the home page with a search bar.
- POST /review: Accepts a product name, scrapes reviews from Flipkart, stores them in MongoDB, and returns the reviews to the user.


## License
This project is licensed under the MIT License.
