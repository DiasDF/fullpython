# GITHUB

## Configurar o GIT

No terminal, execute os comandos:

```Git Config
   git config --global user.name “Seu nome”
   git config --global user.email “Seu e-mail”
```

```

```

# Criar repositório

No terminal, dentro da pasta do projeto, execute o comando:

```Git Init
   git init
```

## COMANDOS GIT
Podemos ver os arquivos que estão sendo considerados pelo Git, que estão no stage, através do comando:

```Git Status
   git status
```

Para adicionar um arquivo ao stage do Git, dizer ao Git que ele deve considerar o arquivo, execute o comando:

```Git Add
   git add nome_do_arquivo
```

ou

```

```

git add .
#Com um espaço e ponto ao final: ele adicionará todos os arquivos do diretório ao stage

Para remover o arquivo do stage:

```

```

git rm --cached nome_do_arquivo

Podemos salvar a alteração e criar um commit:

```

```

git commit -m "minha mensagem entre aspas duplas"

Podemos adicionar o arquivo ao stage e já salvar a alteração, trata-se da execução do comando:

```

```

git commit -am "minha mensagem"

Padrões para nomear commits
O padrão para escrever as mensagens para os commits é: Chore; Fix; Feat; Docs

\*Chore: usado para pequenas tarefas:

```

```

git commit -m “chore: removendo arquivo.txt”

\*Fix: correções:
git commit -m “fix: correção no cálculo de médias”

\*Feat: inclusão de funcionalidade:
git commit -m “feat: inclusão de função para calcular mediana”

\*Docs: atualização de documentação:
git commit -m “atualizando o changelog.md”

Visualizar o registro de commits realizados
O registro de um commits é composto por:
Commit: identificador único do commit
Author: autor do commit
Date: data em que o commit foi feito

Para visualizar o histórico de commits, use o comando:
git log

Para visualizar os últimos dois commits:
git log -n 2\*

Para visualizar uma versão resumida do registro de commits:
git log --oneline

visualizar o registro de uma forma mais detalhada solicitando o conteúdo da alteração, através do comando:
git log --stat

Combine variações, solicite o conteúdo de dois registros com apenas o identificador do commit:
git log --stat -n 2 --oneline

Desfazer alterações
Podemos desfazer alterações em arquivos que >> ainda não foram adicionados ao stage <<, usando o comando:
git checkout meu_arquivo

Navegar entre commits
Com o Git podemos viajar no tempo, para o passado, podemos voltar o
conteúdo de um repositório para o conteúdo de um determinado commit com
o seguinte comando git checkout COMMIT_ID

Reverter commits
Uma reversão significa que outro commit será criado desfazendo a alteração;
Se incluirmos um arquivo no commit que queremos reverter, outro commit será criado removendo este arquivo, isso é feito através do comando:
git revert HEAD COMMIT_ID
# Criar repositório

No terminal, dentro da pasta do projeto, execute o comando:

```Git Init
git init
```
Listar as branches
Para visualizar todas as branches que fazem parte do repositório, execute o comando:
git branch

```

```
