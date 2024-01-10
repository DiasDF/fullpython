# Powershell - windows

# Terminal MacOs: OBS use o botão "command" no lugar de "ctrl"

"dir" ou "ls" - Listagem de arquivos.

"Tab" - completa nomes de comandos.

“ctrl+L” - Limpa a Tela do Terminal.

"command+l" - Desfaz o último comando.

"cd .." - Para sair da pasta.

"cd ." - Para entrar na pasta.

"mkdir" - Criar uma pasta.

"echo" - Criar um arquivo dentro da pasta.

Ex. C:\Users\gianc\Pasta_exemplo> echo "olá" > arquivo.txt

"cat" - Para ver o conteúdo dentro do arquivo.

"rm -r" - Para deletar tanto o arquivo quanto a pasta.

"git config --global user.name "nome" - Para configuração básica do Git.

"git status" - Para saber o status do projeto.

"git add" - Adiciona esse arquivo para o Stage (carrinho, arquivos add com git add que estão “verdes” prontos para o commit).

"git rm --cached - Remover arquivo do Stage (git add .) do Git .

"git add ." - Adiciona todos arquivos para o Stage.

"git commit -am “Texto”. Faz o add e o commit ao mesmo tempo.

CRIAR A PASTA GIT NA RAIZ HOME
“cd ~ “
“mkdir gitpython”

“pwd “ Ver o caminho completo do diretório atual
./Users/diasdf/gitpython.

”shift+option+command+c ou v” : copia e cola conteúdos da tela do terminal macos.

Instalar o comando "code ." no VSCode MACOS:
No VSC digite “shift+command+p” + “install 'code’ command path”

Criar chagelog.md
https://keepachangelog.com/pt-BR/1.0.0/

Padrões para nomear commits
O padrão para escrever as mensagens para os commits é:

Chore: usado para pequenas tarefas:
"git commit –m “chore: removendo arquivo.txt”"

Fix: correções:
"git commit –m “fix: correção no cálculo de médias”"

Feat: inclusão de funcionalidade:
"git commit –m “feat: inclusão de função para calcular mediana”"

Docs: Atualização de documentação.
"git commit –m “docs: atualizando o changelog.md”"

Tipos de mudanças

    Added/Adicionado para novos recursos.
    Changed/Modificado para alterações em recursos existentes.
    Deprecated/Obsoleto para recursos que serão removidos nas próximas versões.
    Removed/Removido para recursos removidos nesta versão.
    Fixed/Corrigido para qualquer correção de bug.
    Security/Segurança em caso de vulnerabilidades.

"Shift+Command+v" : Markdown preview
Mostra com fica a saída do md.

"fn+F1 = shift+command+p" - configurações do VsCode

"git log -n 3" - Lista os 3 últimos logs

"git log --oneline" - Lista os log em 1 linha resumido

"git log --stat" - Mostra também os arquivos modificados.

"git log --stat –n 2 --oneline" -

Instalar Plugin VsCode: Git History

fn+F1 : git view history (gitlog)

"git checkout" : Desfaz alterações do commit

"git revert HEAD idDoGit" : Desfaz o commit pelo id

"git checkout master" : Muda a branch para master

"git branch newBranche" : Cria uma nova branch

"git checkout -b newBranch-b" : cria a "newBranch-b" e ja deixa ela como ativa clonando os dados da branch anteriormente ativa

"git branch branch-c master" : Cria a branch-C clonando ela da master

"git branch -D branch-a" : O -D (maiúsculo) Delera a branch-a

"git checkout -b feature/new_file" : Cria uma nova branch new_file do tipo feature e seta como ativa

"git merge feature/new_file" : Estando na branch mastes ele irá Mesclas a branch feature/new_file a master.


