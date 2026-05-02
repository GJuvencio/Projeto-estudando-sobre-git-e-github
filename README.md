Meu projeto de Git.

git init
- iniciar novo projeto com git

git add <nome-arquivo>/.
- add os arquivos estão prontos para serem commitados

git commit -m "mensagem commit"
- commit os arquivos no histórico

git log
- mostra os últimos commit, log de alterações

git status
- como está o estado da nossas ramificações

git diff
- mostra o que foi alterado
- o que tem de alteração na ramificação

git merge
- merge de ramificação, mesclar ramificações

git branch
- mostra a branch atual

git checkout <nome-branch>
- muda pra essa branch

git branch -b <nome-da-branch>
- criar uma nova branch a partir da branch atual que estamos

git remote add <nome> <url>
-add um novo repositorio remoto

git push <nome> <nome-da-branch>
- manda nossas alterações locais para o repositório rmoto, para cada branch

git pull <nome> <nome-da-branch>
- pega as alterações do repositório remoto, e joga pra nossa máquina

git fetch
- atualiza o novo histórico local de acordo com o histórico salvo la no repositório remoto
- sincronização do local com o remoto