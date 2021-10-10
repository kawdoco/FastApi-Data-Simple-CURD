uvicorn sql_app.main:app --reload
npm run dev


cd ~/workspace/my-webpage

# below commands copied from above image.
echo "# html-css-js" >> readme.md
git init
git add readme.md
git commit -m "first commit"
git remote add origin git@gitlab.com:susara123/fastapi.git
git push -u origin master

cd ~/workspace

git clone git@github.com:ohralathe/html-css-js.git

cd html-css-js
# below commands copied from above image.
echo "# html-css-js" >> readme.md
git add readme.md
git commit -m "first commit"
git push -u origin master
# way 1
git branch your-branch-name

# a new branch <your-branch-name> was created and cloned from current branch and current branch will not switch to new branch


# way 2
git checkout -b your-branch-name
