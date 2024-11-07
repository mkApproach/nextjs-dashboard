Set-ExecutionPolicy -ExecutionPolicy RemoteSigned -Scope Process 

echo "# next-todo-app" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/mkApproach/nextjs-dashboard.git
git push -u origin main