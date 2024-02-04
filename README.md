### merge_conflito


criar no github um repositorio. 


criar uma pasta no windows explorer
abrir git bash
fazer git init para iniciar o repositorio.
copiar o repositorio do projeto no github para cá.


abrir vscode com comando code . e criar dois commits:
1 commit com as paginas index e vendas
e outro commit com um valor para as vendas.
fazer git add . e git commit e push para o github.
criar outra branch com nome ft-pedidos.


em outra pasta no windows explorer vou clonar o projeto do github, como se fosse outro desenvolvedor.
vou para essa pasta.
crio a branch ft-login
no vscode do projeto crio pagina de login e edito pagina de index
faço git add . e git commit
mudar para branch main
fazer pull origin main para atualizar local em relacao ao github
git checkout ft-login
git merge main (ft-login) pra juntar a main aqui, mas ja esta tudo atualizado mesmo
git push -u origin ft-login
pronto esse desenvolvedor terminou o trabalho dele.
vou no github e faço o pull request, e depois a equipe vai autorizar o merge pull request.



agora volto pro meu codigo como dev
faço uma edicao na pagina la no vscode em index e pedidos.
faço git add . e git commit
depois git log --oneline
git checkout main 
git pull origin main agora ja vem varias atualizacoes do github, pq o outro desenvolvedor trabalhou la no ft-login
git log --oneline vemos que o main agora tem mais commits porque o outro desenvolvedor fez uma feature no ft-login
git checkout ft-pedidos
git merge main (ft-pedidos) vai juntar o merge com o main
**ATENCAO ele avisa que tem conflito ! tem conflito no arquivo index! tem que resolver o conflito, para depois eu dar o commit !!
vou la no vscode para analisar o codigo e resolver o conflito, para depois eu fazer o commit.
git status
e faço o git add . git commit -m 
e por fim o git push -u origin ft-pedidos
pronto, esta feito o 2° merge, posso ir conferir no github. a equipe vai avaliar o merge e autorizar o pull request.




