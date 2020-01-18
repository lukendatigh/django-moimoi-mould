# Django MoiMoi Mould
Django MoiMoi Moild is a non-bloated and flexible boilerplate for quickly setting up Django projects.

## Setup
1. Clone repository
2. Run `pipenv shell` to create virtual environment
3. Run `pipenv install --dev` to install packages, including development packages
4. Edit `.env` with your own variables and uncomment it from the  `.gitignore` file
5. Rename the project by running `python manage.py rename your-new-project-name-`

### Included
1. [Django Web Framework](https://www.djangoproject.com/)
2. [django-storages](https://django-storages.readthedocs.io/en/latest/) and [boto3](https://boto3.amazonaws.com/v1/documentation/api/latest/index.html)
3. [Pillow](https://python-pillow.org/) 
4. [Python decouple](https://pypi.org/project/python-decouple/)
5. Multipe settings files (development and production)

#### Note 
Before pushing to production, modify `manage.py` by changing `'demo.settings.development'` for development settings to `'demo.settings.production'` for production settings


### Dev Packages
1. [Django debug toolbar](https://github.com/jazzband/django-debug-toolbar) 


### Other useful commands
1. Install new packages `pipenv install your-package-name` 
2. Lock dependencies `pipenv lock` 
3. Check dependency tree `pipenv graph`
4. Reverse dependency tree `pipenv graph --reverse`
5. Remove all dependencies `pipenv uninstall --all`
6. Get virtual environment location `pipenv --venv` 
7. Get project root location `pipenv --where` 
