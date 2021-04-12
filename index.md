cd
echo "# docs" >> index.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:zyl15735648281/docs.git
git push -u origin main
