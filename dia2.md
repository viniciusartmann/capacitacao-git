# Capacitação de git para o Avoante Aeromec
## Dia 2
### Setup inicial
1. Configure seu nome de usuário: `git config --global user.name "rubemnobre"`
1. Configure seu email: `git config --global user.name "rubemjrx@hotmail.com"`

### Repositório
O git tem objetivo de gerenciar os arquivos de um projeto, ele consegue armazenar um histórico de alterações e gerenciar versões paralelas (branches), entre outras funções.
Um repositório é um envólucro para um projeto.

#### Inicializando um repositório
##### Do zero
1. Crie uma pasta no local onde deseja: 
    1. Navegue para o local utilizando `cd`
    1. Crie a pasta utilizando `mkdir`
    1. Navegue até a pasta utilizando `cd`
1. Inicialize o repositório utilizando o comando `git init`
1. Você já pode começar a utilizar o repositório.

##### Em um projeto já iniciado
1. Navegue até a pasta onde o projeto está utilizando `cd`
1. Inicialize o repositório utilizando o comando `git init`

#### Clonando um repositório
1. Copie o link do repositório. Exemplo: o link deste repositório é https://github.com/aeromec/capacitacao-git
1. Navegue até a pasta onde quer colocar o repositório utilizando `cd`
1. Clone o relatório utilizando o comando `git clone https://link.do.repositorio/`

### Commit
Já foi dito que o git é capaz de armazenar o histórico de alterações de um projeto. Os pontos na história que são armazenados são os commits.

#### Status
Para ver as alterações desde o último commit, utilize o comando `git status`

Ele irá listar quais arquivos foram modificados desde o último commit.

#### Add
Para adicionar os arquivos modificados ou criados ao commit, utilize o comando `git add arquivo.txt` para cada arquivo listado em vermelho ("Untracked files" e "Changes not staged for commit") pelo comando `git status`. Se sentir segurança de que não há nenhum arquivo indesejado na pasta, utilize `git add .`, que adicionará todos os arquivos dela.

#### Fazer o commit
