
# MindFull Logs

The Blog Application is a dynamic web platform that enables users to share their thoughts and ideas with the world. It offers a range of essential features, providing a seamless experience for both writers and readers.


## Features

- User Registration and Authentication
- Subscription Options
- Bookmarking
- Comments and Replies
- Tags and Search Functionality
- Featured Post


## Getting Started
To run the Blog Application locally, follow these steps:
1. Clone the repository to your local machine.
2. Set up a virtual environment and install the required dependencies using 
```bash
pip install -r requirements.txt
```
3. Configure your AWS S3 and RDS PostgreSQL credentials in the settings file.
4. Run the migrations to create the database using 
```bash
python manage.py migrate
```
5. Start the development server with
```bash
python manage.py runserver
```
6. Access the application on http://localhost:8000/ in your web browser.

## Technologies Used
*  Backend: Django
* Frontend: HTML, CSS,Bootstrap
* Hosting: Render
* Static Files: AWS S3
* Database: AWS RDS PostgreSQL
## Contributing

Contributions to the Blog Application are welcome. If you find any issues or have suggestions for improvements, please open a new issue or submit a pull request.

