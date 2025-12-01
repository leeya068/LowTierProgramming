## Low Tier Programming

Repository for Low Tier Programming's WIX1002 (Fundamentals of Programming) Semester 1 25/26 Project.

CREATE YOUR OWN BRANCH (DO THIS IF THIS IS YOUR FIRST TIME EDITING A CODE):
1. git clone <repo URL>
2. git checkout -b yourname-feature

Workflow when you want to edit your code:
DO this inside your command prompt. 
Change directory to the project folder
1. git pull origin main
2. git checkout yourname-feature
3. Edit stuffs you want, once you're done do the steps below:
4. git add <filename>
5. git commit -m "comment  here"
6. git push origin yourname-feature
7. git checkout main
8. git pull origin main
9. git merge yourname-feature
10. git push origin main

CREATE YOUR OWN .ENV FILE:
If you want to run the codes that are related to the AI calls, you need an API key. 
- Go to https://huggingface.co/
- Click on profile picture in top right
- Click "Access Tokens"
- Create new token, name it whatever
- Check everything under "Inference" section. Leave everything else untouched
- Create the key, and copy it
- If you cloned the repository correctly, there should be a "data" folder with Sample.txt inside it.
- Create a new file called ".env"
- Type this into the file: BEARER_TOKEN=pasteyourkeyhere
- Save that, and now you can run the AI calls to test whatever

IMPORTANT !! 
DO NOT ADD OR COMMIT YOUR .ENV FILE TO THE REPOSITORY!!