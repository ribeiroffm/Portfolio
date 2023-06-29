# Comandos de Git
git config --global user.name "Marta"
git config --global user.email "ribeiroffm@gmail.com"

## Comandos
git init --> inicia o repositório
git status --> verifica o estado do repositório
git add NOMEFICHEIRO --> adiciona um ficheiro específico ao repositório
git commit -m "MENSAGEM" --> cria ponto no controlo de versões do repositório com os ficheiros adicionados
git commit -am "MENSAGEM" --> cria um commit e adiciona os ficheiros modificados já adicionados a um commit anterior
do repositório
git log --> mostra as informações de todos os commit feitos
git show CODIGOCOMMIT--> apresenta as alterações efetuadas no commit do código fornecido
git show --> apresenta as alterações efetuadas no último commit
git remote add origin LINK --> liga o repositório atual local a um repositório online
git push -u origin master --> envia a branch master para o repositório online (necessário apenas no primeiro envio)
git push --> enviar o repositório atual local para o repositório online