# Configuração

```git config --global user.name "NOME"```

Configura o nome que você quer ligado as suas transações de
commit

```git config --global user.email "EMAIL"```

Configura o email que você quer ligado as suas transações de commit
<br><br>

# Criar repositório

```git init NOME-PROJETO```

Cria um novo repositório local com um nome específico

```git clone URL```

Baixa um projeto e seu histórico de versão inteiro
<br><br>

# Alteração

```git status```

Lista todos os arquivos novos ou modificados para serem commitados

```git add NOME-ARQUIVO```

Adiciona um arquivo na preparação para versionamento

```git reset NOME-ARQUIVO```

Deseleciona o arquivo, mas preserva seu conteúdo

```git diff```

Mostra diferenças no arquivo que não foram realizadas

```git diff --staged```

Mostra a diferença entre arquivos selecionados e a suas últimas
versões

```git commit -m "MENSAGEM"```

Grava as alterações do arquivo no histórico de versão
<br><br>

# Alteração em grupo

```git branch```

Lista todos as branchs locais no repositório atual

```git branch NOME-BRANCH```

Cria uma nova branch

```git checkout NOME-BRANCH```

Muda para a branch especificada e atualiza o diretório de trabalho

```git merge NOME-BRANCH```

Combina o histórico da branch especificada com o branch atual

```git branch -d NOME-BRANCH```

Exclui a branch especificada
<br><br>

# Refatoração de arquivos

```git rm NOME-ARQUIVO```

Remove o arquivo do diretório de trabalho e o seleciona para remoção

```git rm --cached NOME-ARQUIVO```

Remove o arquivo do controle de versão mas preserva o arquivo
localmente

```git mv NOME-ARQUIVO NOVO-NOME-ARQUIVO```

Muda o nome do arquivo e o seleciona para o commit
<br><br>

# Histórico

```git log```

Lista o histórico de versões para o branch atual

```git log --follow NOME-ARQUIVO```

Lista o histórico de versões para um arquivo, incluindo mudanças de
nome

```git diff NOME-BRANCH...NOME-OUTRA-BRANCH```

Mostra a diferença de conteúdo entre dois branches

```git show HASH-COMMIT```

Mostra mudanças de metadata e conteúdo para o commit especificado
<br><br>

# Reverter commits


```git reset HASH-COMMIT```

Desfaz todos os commits depois de `HASH-COMMIT`, preservando
mudanças locais

```git reset --hard HASH-COMMIT```

Descarta todo histórico e mudanças para o commit especificado

```git revert HASH-COMMIT ```

Reverte o que foi feito no commit especificado, voltando para o commit anterior e criando um novo registro
<br><br>

# Sincronização

```git fetch [marcador]```

Atualiza todo o histórico de um marcador de repositório

```git merge [marcador]/NOME-BRANCH```

Combina o branch utilizada na branch master

```git push -u NOME-BRANCH```

Envia todos os commits da branch local para o repositório remoto

```git pull```

Atualiza o repositório atual com histórico de commits e arquivos mais rescentes