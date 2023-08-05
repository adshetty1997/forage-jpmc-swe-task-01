# JPMC Task 1
Starter repo for task 1 of the JPMC software engineering program

STEPS TO SETUP PYTHON ENV:
- In terminal, run command 'python -m venv "env_name"' or 'python -m venv new_env'
- Enter your "env_name+ in .gitignore file (in case you use your own name for env)
- Install all dependencied with this command 'pip install -r requirements.txt'


STEPS TO CREATING A GIT PATCH FILE:
- Command 'git format-patch -n "name"' where 
    -> name = user_specific_name|HEAD(commit message)  OR "name" can be replaced with "–stdout > file_name.patch"
    -> n = number of commits to patch(starting from the latest).