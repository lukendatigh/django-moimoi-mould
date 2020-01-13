# Django MoiMoi Mould

## Setup
1. Clone repository
2. Run `pipenv shell` to create virtual environment
3. Run `pipenv install --dev` to install packages, including development packages
4. Edit `.env` with your own variables and add uncomment it from the  `.gitignore` file
5. Rename the project by running `python manage.py rename your-new-project-name-`

### Included
1. [Django Web Framework](https://www.djangoproject.com/)
2. [Pillow](https://python-pillow.org/) 
3. [Python decouple](https://pypi.org/project/python-decouple/)
4. Multipe settings files (development and production)

#### Note 
Before pushing to productioon. modify `manage.py` by changing `'demo.settings.development'` for development to `'demo.settings.production'` for production


### Dev Packages
1. [Django debug toolbar](https://github.com/jazzband/django-debug-toolbar) 


### Other useful commands
1. `pipenv lock` to lock dependencies
2. `pipenv graph` to print out tree of dependencies
3. `pipenv graph --reverse` to print out reverse tree of dependencies
4. `pipenv uninstall --all` to uninstall all dependencies
5. `pipenv --venv` to find out where your virtual environment is
6. `pipenv --where` to find out where your project root is 
