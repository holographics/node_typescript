
#### 
````
git clone git@github.com:holographics/node_typescript.git
cd node_typescript/
git checkout -b branch_01
echo "# node_typescript" >> README.md
vim README.md
git add README.md
git commit -m "added README.md"
git push origin branch_01
````
#### …or create a new repository on the command line
````echo "# node_typescript" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin git@github.com:holographics/node_typescript.git
git push -u origin master
````
#### …or push an existing repository from the command line
````
git remote add origin git@github.com:holographics/node_typescript.git
git push -u origin master
…or import code from another repository
````
#### You can initialize this repository with code from a Subversion, Mercurial, or TFS project.

