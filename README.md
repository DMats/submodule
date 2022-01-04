# submodule setup steps

1. Create repo in Github
2. Console commands:
```console
git clone git@github.com:DMats/submodule.git
cd submodule/
echo "# submodule" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M main
git remote add origin git@github.com:DMats/submodule.git
git push -u origin main
```
