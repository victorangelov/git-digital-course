## comandos git/versionamento
* git init     = inicia um repositório git
* git clone    = copia um repositório da internet http
* git status   = ve o status do git
* git add      = manda para o estado staged
* git commit -m "nome da modificação"   = sobe as modificações, use i para inserir esc para sair e :wq para finalizar o commit só para para * comitar após o git add ou o git diff
* git diff     = faz um add mostrando diferenças entre o antes e depois, para fazer o git diff para arquivos que já foram git add use o git diff --staged
* git push     = envia as alterações para o repositório. empurra para algum lugar. 
* git log      = mostra o histórico dos commits realizados. 
* git restore  = remove coisas que foram salvas no trabalho, e sai do changed para retornar a área de change caso já tenha sido dado o git add git restore --staged README.md
* git pull     = puchar de algum repositório as modificações feitas por outras pessoas
* git fech origin     = mostra as modificações do repositorio compartilhado mostra as modificações antes do pull
* git branch nomedaramificação    = cria uma ramificação do código para trabalhos paralelos. 
* git log --oneline --decorate = comando git para ver em qual  branch estamos atualmente. 
* git checkout testing = comando para mudar a branch atual
* git merge testing = está puchando uma ramificação do código que estava sendo trabalhada em paralelo. 
## estados do git
* untracked        = não rastreado 
* unmodified       = já mapeado, já passou para staged e comitado
* modified         = arquivo modificado, precisa subir tem que ir para staged
* staged           = status antes de ser comitado. 

