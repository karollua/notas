
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

```bash
# Aula do dia 19/06/23.
## Configurando o gitbash e o github.
````bash
ssh.ls -al ~/.ssh --> "Verificar se existe chave" 
(ID)ssh-keygen -t ed25519 -C "your_email@example.com"--> "Adicionar uma nova chave."
"$(ssh-agent -s)"-->"Inicializar agente-ssh.eval" 
ssh-add~/.ssh/id_ed25519 --> "Adicionar chave ssh ao agente."
## SSH - chave
ssh.clip < ~/.ssh/id_ed25519.pub--> "Copiar chave" 
"Adicionar chave no githubGithub -> Settings -> SSH and GPG keys -> New SSH key -> Colar*Coloque um título que identifique a chave*" ( em seu perfil no github)
ssh -T git@github.com--> "Testar conexão" ( irá aparecer um texto com duas opções de digitação yes/no, digite -yes-)

