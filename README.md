# BlogWebsite

This is a blog website made with Flask. 
I did not write the JavaScript or styling, as this was a project to improve my Flask and Jinja skills.
Has a SQLAlchemy database with relationships between users and their blog posts and comments.

### Download and run on local computer: 
Make sure [Python](https://www.python.org/) is installed on your computer. Download zip of the BlogWebsite onto your computer./
Navigate through your command line to the location where you installed the project e.g. ~/Users/username/Downloads/BlogWebsite./
Check the 'requirements.txt' file for dependencies. run the command `python -m pip install -r requirements.txt` to download needed dependencies. ([pip](https://pip.pypa.io/en/stable/installation/) needed for this command)/
While in the BlogWebsite working directory, run the command- `export FLASK_APP=app/__init__.py; flask run`. This should start a development server on a local port which you should navigate to in your browser.
