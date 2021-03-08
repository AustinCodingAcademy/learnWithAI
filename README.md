# node-auth-mkdocs-material-ebook

`npm i`
`cd ebook-folder`
?? mkdocs-material install??
`mkdocs build` (will require installation of mkdocs with pip - `pip install mkdocs`)
`mkdocs serve` - serves to port 8000 withOUT username:password authentication
`cd ..`
add `.env` file with environment variables
  
  ```txt
    STUDENT_USERNAME=a-username
    STUDENT_PASSWORD=a-password
    INSTRUCTOR_USERNAME=a-username
    INSTRUCTOR_PASSWORD=a-password
    PORT=5500
  ```

`npm start` - serves to port 5500 with username:password authentication

on start script - cd into ebook, run python for `mkdocs build`

to deploy

mkdocs build
mkdocs serve to test
cd ..
git status, add, commit, push
[In Heroku or other you'll need to setup environment variable using the CLI or the dashboard](https://devcenter.heroku.com/articles/config-vars)

How to install Python and pip instructions here: