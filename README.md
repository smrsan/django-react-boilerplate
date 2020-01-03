# :fried_egg: django-react-boilerplate

An empty project (boilerplate) for using both Django and React.js separately.

# :package: Install

1. Clone the project to your machine: `git clone https://github.com/smrsan/django-react-boilerplate.git`
2. Navigate into the directory: `cd django-react-boilerplate`
3. Source the virtual env: `pipenv shell`
4. Install the backend dependencies: `pipenv install`
5. Navigate into the `frontend` directory: `cd frontend`
6. Install the frontend dependencies: `npm i` or `npm install`

# :rocket: Run The Application

You will need two terminals pointed to the frontend and backend directories to start the servers for this application.

1. Start the backend server in the `backend` directory: `python manage.py runserver` or simply just do `./manage.py runserver` (You have to run this command while you are sourced into the virtual environment)
2. Start the frontend dev server in the `frontend` directory: `yarn start` (This will start the frontend on the address `localhost:3000`)

# :pray: Thanks

Thanks to [@Jordanirabor](https://github.com/Jordanirabor) for writing this [useful article](https://scotch.io/tutorials/build-a-to-do-application-using-django-and-react).
