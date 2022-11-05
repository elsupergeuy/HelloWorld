# HelloWorld
# install homebrew for mac
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"

# create github repo

echo "# HelloWorld" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/elsupergeuy/HelloWorld.git
git push -u origin main
