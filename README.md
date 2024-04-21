# tutorialCommit
linhas de códigos pra dar commit no github pra quem não sabe (eu)

<h1>Primeiro Commit na main branch</h1>
<br>

echo "# [nomedorepositório]" >> README.md<br>
git init<br>
git add README.md<br>
git add .<br>
git commit -m "first commit"<br>
git branch -M main<br>
git remote add origin [link do repositório]<br>
git push -u origin main<br>

<br><br>

<h1>Commit na main branch</h1>
<br>

git init<br>
git config --global user.name "seuusernamenogit"<br>
git config --global user.email "seuemailnogit"<br>
git add .<br>
git commit -m "algum comentário"<br>
git branch -M main<br>
git remote add origin [link do repositório]<br>
git push -u origin main<br>

<br><br>

<h1>Commit em branch separada</h1>
<br>

git init<br>
git config --global user.name "seuusernamenogit"<br>
git config --global user.email "seuemailnogit"<br>
git add .<br>
git commit -m "algum comentário"<br>
git branch -C romulo<br>
git remote add origin [link do repositório]<br>
git push -u origin romulo<br>
