# Eccommerce
Python Django Project - Eccomerce Store
# Core 
-   Develop Basic Application
-   Shopping Cart Functionality
-   Payment Portals Functionality
-   Additionalities Functionality   -   (Different aspects that are 
possibly wanted to be added to Project)

# step 1 
- Start W/ Django
- Models & Admin
    # - Creating simple Admin area to   start adding data to the DataBase 
    # - import images, Setup Media folder
- testing -> Models
    # Using the package called Coverage to guide in Testing
- URL's, Views
- Templates -> Bootstrap
    # Bootstrap framework (HTML & CSS framework) to quickly build Views
    - Connect views with a html & CSS template which will be distributed for the user to see so they can see the website I'm building
- Testing -> Views
- PEP 8 
     Python Style Conventions
    # must install some python packages to test code & make sure it meets the PEP 8 Standards

# Visual Studio Code
    - Extensions 
        -   Python 
            # Provides Formating, linting (showing me where I might of made a mistake) & etc
        -   Django
            # Highlights code & gives me code suggestions
        -   SQLite
            # Allows access for me to have a look into the database


create venv (virtual enviornment file to install individual packages away from the main computer & the main version of python on this machine

manage.py file - allows access to django admin functionality

core file - the core application itself

store file - to build up model and Database & so on


understanding tables 
    - The columns make up the feilds & structure of the table
    - The Columns will hold or rows which represent individual records in our table


Tables SQLite
- Django automatically builds an ID an auto incremented number having the primary key associated to all of the different feilds
    
Basic VENV config

Create venv
    - in command prompt terminal
         - py -m venv venv
<<<<<<< Updated upstream
        Activate - venv\Scripts\activate 
        - Next, pip install django, in the venv
=======
        Activate - venv\Scripts\activate 
        - Next, pip install django, in the venv
>>>>>>> Stashed changes

WORK FLOW BASICS
    - User enters url HTML request or domain into web browser
    - django searchers for this url in your application 
    - if the request matches a URL in the system That URL will connect to the view
    - the view is connected to the database, and template, etc.
    then the template is sent back to the user with all of the data inserted 


