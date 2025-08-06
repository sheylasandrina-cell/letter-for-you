# open terminal and navigate to your project folder
cd path/to/your/project

# initialize git and commit your files
git init
git add index.html styles.css script.js
git commit -m "Initial commit"

# connect to your remote GitHub repo (replace USERNAME and REPO)
git remote add origin https://github.com/USERNAME/letters-for-you.git

# push files to GitHub
git branch -M main
git push -u origin main
