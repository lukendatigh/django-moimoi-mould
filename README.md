# Django MoiMoi Mould
Django MoiMoi Moild is a non-bloated and flexible boilerplate for quickly setting up Django projects.

## Setup
1. Clone repository
2. Run `pipenv shell` to create virtual environment
3. Run `pipenv install --dev` to install packages, including development packages
4. Edit `.env` with your own variables and add uncomment it from the  `.gitignore` file
5. Rename the project by running `python manage.py rename your-new-project-name-`

### Included
1. [Django Web Framework](https://www.djangoproject.com/)
2. [django-storages](https://django-storages.readthedocs.io/en/latest/) and [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
3. [Pillow](https://python-pillow.org/) 
4. [Python decouple](https://pypi.org/project/python-decouple/)
5. Multipe settings files (development and production)

#### Note 
Before pushing to productioon, modify `manage.py` by changing `'demo.settings.development'` for development to `'demo.settings.production'` for production


### Dev Packages
1. [Django debug toolbar](https://github.com/jazzband/django-debug-toolbar) 


### Other useful commands
1. `pipenv install your-package-name` to install new packages
2. `pipenv lock` to lock dependencies
3. `pipenv graph` to print out tree of dependencies
4. `pipenv graph --reverse` to print out reverse tree of dependencies
5. `pipenv uninstall --all` to uninstall all dependencies
6. `pipenv --venv` to find out where your virtual environment is
7. `pipenv --where` to find out where your project root is 
