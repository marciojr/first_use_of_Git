git config --global user.name "marciojr"

git config --global user.email "mmcj@cin.ufpe.br"

cd Desktop

git clone https://github.com/marciojr/if686

git add 20150319.hs

git status

git commit -m "uma mensagem do commit"

git push origin master

e seja feliz

echo # first_use_of_Git >> README.md


git init

git add README.md

git commit -m "first commit"

git remote add origin https://github.com/marciojr/first_use_of_Git.git

git push -u origin master