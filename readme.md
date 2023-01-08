# Git fundamentos

| Comando | O que faz |
| ----- | ----- |
| git init | Inicia um repositório local, criando os arquivos de configuração do git. |
| git status | Verifica o estado dos arquivos do repositório. |
| git add NOME-ARQUIVO | Adiciona um ou vários arquivos para que o git saiba da existência deles e comece a versiona-los. |
| git commit -m MENSAGEM | Salva as alterações feitas e descreve o que foi feito. |
| git remote add origin LINK-DO-GITHUB | Linka o repositório local ao repositório remoto, assim, quando fizer commit, irá para o repositório remoto. |
| git push -u origin BRANCH | Envia os arquviso do repositório local para o repositório remoto na branch escolhida. |
| git log | Mostra o histórico de commits com data, autor e nome dado ao commit. |
| git revert HASH-COMMIT | Revert o que foi feito no commit escolhido, voltando para uma versão anterior e salva em uma nova versão. |
| git branch | Mostra as branchs atuais |
| git branch NOME-BRANCH | Cria uma branch com o nome escolhido |
| git switch NOME-BRANCH | Altera a branch atual para branch escolhida |