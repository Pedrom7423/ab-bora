my project

git init
-iniciar novo projeto com git

git add nome-arquivo
-add os arquivos que estão prontos para serem commitados

git commit -m "nome"
-commit os arquivos no histórico

git log
-mostra os ultimos commit, log de alterações

git status
-como está o estado da nossa ramificação

git diff
-que mostra o que foi alterado

git merge
-merge de ramificações, mescla ramificações

git branch
-mostra a branch atual

git branch -b nome-da-branch
-cria nova branch a partir da atual

git checkout nome-branch
-muda para essa branch

git remote add nome url
-add um novo repositório remoto

git push nome nome-da-branch
-manda nossas alterações locais para um repostório remoto

git pull nome nome-da-branch 
-pega as alterações do repositório remoto e joga para nossa máquina

git fetch
-atualiza o novo histórico de acordo com o histórico salvo lá no repositório
-sincronização com o local remoto