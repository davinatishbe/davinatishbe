npx create-react-app my-react-app
cd my-react-app
git init
git add .
git commit -m "Initial commit"
gh repo create my-react-app
git checkout -b update_logo
git add .
git commit -m "Update logo and link"
git push origin update_logo
gh pr create --base master --head update_logo --title "Update Logo and Link"
gh pr merge <PR_NUMBER>

