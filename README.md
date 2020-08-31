# how_to_use_git

## …or create a new repository on the command line
echo "# how_to_use_git" >> README.md
git init
git add README.md
git commit -m "first commit"
git branch -M master
git remote add origin https://github.com/gcaussi/how_to_use_git.git
git push -u origin master

## …or push an existing repository from the command line
git remote add origin https://github.com/gcaussi/how_to_use_git.git
git branch -M master
git push -u origin master

## Basic Git commands
git init                             // inicia a linha do tempo
git add                              // adiciona ou atualiza mudanças para irem para a linha do tempo
git commit                           // adiciona um ponto na linha do tempo
git log                              // visualiza os pontos na linha do tempo / commit
git status                           // informa o estado das alterações do nosso projeto
git show                             // apresenta determinado ponto na história
git branch                           // gerenciar novas linhas do tempo
git checkout                         // manipula as linhas do tempo
git merge                            // une as linhas do tempo
git push                             // envia alterações locais para o repositório remoto
git config credential.helper store   // salva o login e senha, não sendo necessário a credencial toda vez
