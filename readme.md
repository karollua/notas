
# Inicializando git local




Primeiro confira se o git está instalado:




```bash

git --version ""

```




segundo passo




# Configurar o Git




```bash

git config --global user.name "nome"

git config --global user.email "email"

```

terceiro passo




# Inciar - local




```bash

cd documents

mkdir

cd arquivo

git init

```




# Comandos do git

 ```bash

 Git status --> "permite inspecionar quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git."

 ````

 ````bash

 git add < filename ou .> --->  "adiciona uma alteração no diretório ativo à área de staging.diz ao Git que você quer incluir atualizações a um arquivo específico no próximo commit."

 ````

 ````bash

git restore --staged <filename ou .> --> "faz o mesmo que o reset , ele apenas vai fazer com que o HEAD aponte para o último commit, ou seja vai remover o arquivo com mudanças da área de stage."

````

````bash

git branch <branchname> --> "permite criar, listar, renomear e excluir ramificações. Ele não permite alternar entre as ramificações ou reunir um histórico bifurcado de novo."

````

````bash

git checkout <branchname> --> "permite navegar entre ramificações criadas pelo git branch . A verificação de uma ramificação atualiza os arquivos no diretório atual para que fique igual à versão armazenada nessa ramificação e diz ao Git para gravar todos os novos commits nessa ramificação."

````

````bash

git checkout -b <branchname> --> "Cria a branch e muda para ela."

````

````bash

git commit -m "<description>" --> "usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do Git."

````

````bash

git pushgit ---> " é usado para enviar o conteúdo do repositório local para um repositório remoto"

````

````bash

git branch -D <branchname> -->

````

````bash

git fetch--> "é um comando básico usado para baixar conteúdos de um repositório remoto. O git fetch é usado em conjunto com git remote , git branch , git checkout e git reset para atualizar um repositório local ao estado de um remoto."

````

````bash

git pull --> "é usado para buscar e baixar conteúdo de repositórios remotos e fazer a atualização imediata ao repositório local para que os conteúdos sejam iguais. Fazer o merge de alterações upstream remotas no repositório local é algo comum em fluxos de trabalho de colaboração baseados em Git."

```


