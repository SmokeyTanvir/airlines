# Flight Management System
This is a Flight Management System project that allows users to view available flights, their details, and add passengers to a specific flight. It provides a user-friendly interface for managing flights and passenger information.

## Features
<ul>
  <li>View a list of available flights</li>
  <li>Display detailed information about a specific flight</li>
  <li>Add passengers to a flight</li>
  <li>Simple and intuitive user interface</li>
  <li>Integration with the Django web framework</li>
</ul>

## Technologies Used
<ul>
  <li>Python</li>
  <li>Django</li>
  <li>HTML</li>
  <li>CSS</li>
</ul>

## How to Run the Project
<ol>
  <li>Clone the repository to your local machine.</li>
  <li>Make sure you have Python and Django installed.</li>
  <li>Set up a virtual environment (optional but recommended).</li>
  <li>Install the required dependencies using : <b>pip install -r requirements.txt</b> .</li>
  <li>Apply migrations to set up the database using <b>python manage.py migrate</b>.</li>
  <li>Run the development server with the command <b>python manage.py runserver</b> .</li>
  <li>Access the application in your web browser at <b>http://localhost:8000</b>.</li>
</ol>
  
## Project Structure
<ul>
  <li>flights/ - The main Django application folder.</li>
    <ul>
      <li>templates/flights/ - Contains HTML templates for the application's views.</li>
        <ul>
          <li>layout.html - Base template used for all pages.</li>
          <li>index.html - Template for displaying the list of flights.</li>
          <li>flight.html - Template for displaying detailed information about a flight and managing passengers.</li>
        </ul>
      <li>models.py - Defines the Flight and Passenger models.</li>
      <li>views.py - Contains the view functions for rendering the templates and handling form submissions.</li>
      <li>urls.py - Configures the URLs for the application's views.</li>
   </ul> 
  <li>airlines/ - The Django project folder.</li>
  <li>manage.py - Command-line utility for managing the Django project.</li>
</ul>

## Contributing
Contributions are welcome! If you find any issues or want to enhance the functionality, feel free to open a pull request.

## Live
  View the project live at : ```SmokeyTanvir.pythonanywhere.com```

## Acknowledgements
This project was developed as part of a learning exercise.
The project structure and code organization were inspired by best practices in Django development.
Thank you for checking out the Flight Management System project! If you have any questions or feedback, please let us know.
