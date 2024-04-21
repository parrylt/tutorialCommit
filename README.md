# tutorialCommit
linhas de códigos pra dar commit no github pra quem não sabe (eu)

<h1>Primeiro Commit na main branch</h1>
<br>

echo "# [nomedorepositório]" >> README.md
git init
git add README.md
git add .
git commit -m "first commit"
git branch -M main
git remote add origin [link do repositório]
git push -u origin main

<br><br>

<h1>Commit na main branch</h1>
<br>

git init
git config --global user.name "seuusernamenogit"
git config --global user.email "seuemailnogit"
git add .
git commit -m "algum comentário"
git branch -M main
git remote add origin [link do repositório]
git push -u origin main

<br><br>

<h1>Commit em branch separada</h1>
<br>

git init
git config --global user.name "seuusernamenogit"
git config --global user.email "seuemailnogit"
git add .
git commit -m "algum comentário"
git branch -C romulo
git remote add origin [link do repositório]
git push -u origin romulo
