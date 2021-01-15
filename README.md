# arco-react-sample
App for React Development Coding Sample

Simple To-Do List project taken from tutorial found here: https://www.digitalocean.com/community/tutorials/build-a-to-do-application-using-django-and-react

Instructions for Sample Submission

### 
1. at website https://github.com/arco-data-design/arco-react-sample select 'Use This Template'
2. follow steps to create your repository on github
3. clone repository locally (git clone http://github.com/YOU/YOUR_REPO)
4. move to project directory ('YOUR_REPO')
5. create and activate python virtual environment
    * https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/
    * google can help you find alternate instructions for your OS
6. install python requirements for the sample:
    * pip install -r backend/requirements.py
7. migrate to simple sqlite3 database:
    * python backend/manage.py migrate
8. run backend server:
    * python backend/manage.py runserver
    * leave this running in a shell window. API calls for the sample will be processed here
    * checkout REST API interface: http://127.0.0.1:8000/api/todos/
9. frontend setup
    * install yarn (https://classic.yarnpkg.com/en/docs/install)
    * move to arco-react-sample/frontend and run:
        * npm install
    * then run:
        * yarn start
10. Access the frontend app:
    * http://localhost:3000/
11. Read the below requirements from the 'client'. Choose a scope that you can think you can complete in 1 hour.
    * the 'clock' starts now - we'll use the honor system, we'd like to know how much quality coding you can accomplish in an hour
    * don't worry if you don't complete everything listed, or if you only focus on a small piece. We understand you have to get oriented first.
    * please don't spend more than 1 hour coding - respect your time :-)
12. Begin work 
13. Commit changes with message on your new feature(s)
14. push commits to your github project, make it public and email the link to contractors@arcodd.com
### 
