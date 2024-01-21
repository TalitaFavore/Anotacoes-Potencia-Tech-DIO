# Comandos Git Úteis
- **git init** -> inicializa um diretório como um repositório .git
  
- **git branch** -M main -> define o nome da *branch* principal como *main*
  
- **git clone https:.....** -> clona um repositório remoto para o repositório local
  
- **git remote add origin https:.....** -> vincula um repositório local com um repositório remoto
  
- **git add nomeArquivo** -> adiciona as modificações para a *staging area*
  
- **git add .** -> adiciona todas as modificações para a *staging area*
  
- **git commit -m "first commit"** -> realiza o *commit* das alterações junto com uma mensagem descritiva sobre o *commit*
  
- **git push -u origin main** -> manda o repositório local para o repositório remoto
  
- **git pull** -> puxa as informações do repositório remoto e mescla com o repositório local
  
- **git restore nomeArquivo** -> desfaz as alterações no arquivo e o restaura ao último estado commitado
  
- **git reset --soft HASH** -> desfaz o *commit* até o estado indicado pelo *HASH*, mantendo as alterações na *staging area*
  
- **git checkout -b nomeBranch** -> cria uma nova *branch* e muda para ela
  
- **git checkout main** -> volta para a *branch* main
  
- **git merge nomeBranch** -> mescla a *branch* informada com a *branch* atual (geralmente *main*)
  
- **git branch** -> mostra todas as *branches* existentes
  
- **git branch -d nomeBranch** -> deleta a *branch* informada (use -D para forçar a exclusão, mesmo se houver alterações não mescladas)
