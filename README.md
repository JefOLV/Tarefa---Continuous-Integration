# Tarefa---Continuous-Integration
Execução da tarefa - VSCODE - Guia completo no docs (https://docs.google.com/document/d/1hymhcGKZMxtTU6H_je237F-PjKT8ASgyJI728uG23FE/edit?usp=sharing)

echo 01 > arquivo.txt
git add arquivo.txt
git commit -m "primeiro commit" 
git push

echo 02 > arquivo.txt
git diff
git add arquivo.txt
git commit -m "segundo commit"
git push

echo 003 > arquivo.txt
git diff
git add arquivo.txt
git commit -m "terceiro commit"
git push 

criei um novo arquivo com nome  ".gitignore"
echo *.txt > .gitignore
