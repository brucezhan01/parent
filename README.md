# parent (experiment project)

How to create a submodule

1. git clone https://github.com/brucezhan01/parent.git parent
2. cd parent
3. (git status)
4. git submodule add https://github.com/brucezhan01/child.git
5. (git status)
6. git commit -am "add a new submodule"
7. git push origin master


How to clone a project with submodule

1. git clone https://github.com/brucezhan01/parent.git
2. cd parent
3. git submodule update --init --recursive
or 
1. git clone --recursive https://github.com/brucezhan01/parent.git

How to delete a submodule

1. cd parent
2. git delete child
3. git commit -am "..."
4. git push origin master
