# Django Docker Base
1. Clone the Repo
2. Run the following commands

`docker-compose build`

`docker-compose up`

3. To run commands in the development environments:

`docker-compose run --rm app sh -c "<django commands>"`

E.g.:

`docker-compose run --rm app sh -c "python manage.py makemigrations"`

`docker-compose run --rm app sh -c "python manage.py startapp users"`

And many more. 

4. Github workflows, testing and linting are preconfigured. Just create your tokens from dockerhub and configure actions.
