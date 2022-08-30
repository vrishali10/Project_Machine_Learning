# Project_Machine_Learning

### Software and account Requirement.
1. Github Account
2. Heroku Account
3. VS Code IDE
4. GIT cli
5. GIT Documentation (https://git-scm.com/docs/gittutorial)

Creating conda environment
'''
conda create -p venv python==3.7 -y
'''
To activate conda env
'''
conda activate venv/
'''

OR

'''
conda activate venv
'''

To insatll requirements.txt file
'''
pip install -r requirements.txt
'''

To Add files to git
'''
git add .
'''

OR

'''
git add <file_name>
'''

Note: To ignore file or folder from git we can write name of file/folder in .gitignore file

To check the git status
'''
git status
'''
To check all version maintained by git
'''
git log
'''
To create version/commit all changes by git
'''
git commit -m "message"
'''
To send version/changes to github
'''
git push origin main
'''
To check remote url
'''
git remote -v
'''

To setup CI/CD pipeline in hersku we need 3 information
1. HERAKU_EMAIL = vrishali1357@gmail.com
2. HERAKU_API_KEY = <>
3. HERAKU_APP_NAME = mlproject-1-ineuron


To build docker image
'''
docker build -t <image_name>:<tagname> .
'''
Note: Image name for docker must be lowercase

To list docker image
'''
docker images
'''
Run docker image
'''
docker run -p 5000:5000 -e PORT=5000 f8c749e73678
'''
To check running container in docker
'''
docker ps
'''
Tos stop docker conatiner
'''
docker stop <container_id>
''' 

'''
python setup.py install
'''

Install ipykernel
'''
pip install ipykernel
'''