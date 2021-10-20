<img src="C:\Users\Eduzz 220\Pictures\git-github.jpg" alt="Desafio" style="zoom:50%;" />

# Projeto sobre Git/GitHub da Dio

Repositório criado para o Desafio do projeto

## Links complementares

- [Documentação Git](https://git-scm.com/docs/git#_git_commands)

- [Download Git](https://git-scm.com/download/win)

- [Guia Markdown](https://www.markdownguide.org/basic-syntax/)

## Comandos Básicos Git

- **cd** nomePasta //seleciona a pasta que você queira entrar
- **cd ..**        //volta um nível de pasta
- **cls** limpa o terminal.
- **Ctrl + l** ctrl+l //limpa seu terminal.
- **git add <nomeDoArquivo>**: envia o especificado para o Stage.
- **git add - -all** envia todos os arquivos para o Stage.
- **git checkout <nomeDaBranch>:** alterna para a branch especificada.
- **git checkout -b <nomeDaBranch>:** cria uma nova branch.
- **git commit -m “tituloDoCommit:** envia o que está no Stage para o HEAD.
- **git init** inicializa um repositório local git.
- **git-mv** Move ou renomeia um arquivo, um diretório ou um link simbólico.
- **git-restore** Restaura os arquivos das árvores de trabalho.
- **git remote add origin urlDoRepositorio:** adiciona e indica a URL do repositório remoto em que os arquivos serão mantidos.
- **git status** verifica o estado dos arquivos.
- **git push origin master:** envia os arquivos para o repositório remoto que você especificou através da URL do comando acima.
- **mkdir** <nomeDoArquivo>: cria uma nova pasta.
- **TAB** Ao digitar o começo de alguma palavra/comando ele faz o auto complete.
- **ls** -a comando para mostrar pasta oculta no git bash.

## Dicas Git - GitHub Básico

#### Etapas para fazer commit

1. ##### Iniciando repositório no Git

git init //inicia nossa máquina para um novo commit

2. ##### Adicionando arquivos no commit

git add .  //seleciona todos arquivos da pasta para commitar

3. ##### Iniciando commit com comentário

git commit -m "primeiro commit"

4. ##### Lista de todos configurações do Git

git config --list

5. ##### Cadastrar usuário/email para novo commit

git config --global --unset user.name Meu Nome Aqui

git config --global --unset user.email "email@email.com"

6. ##### Adicionando origin do GitHub

git remote add origin https://linkaqui.com.br 

7. ##### Mostrar link dos repositórios cadastrados

git remote -v

8. ##### Empurrando arquivos para o GitHub

git push origin master

9. ##### Pegando arquivos do GitHub para atualizar com o da sua máquina

git pull origin master

10. ##### clonar repositório

git clone https://linkaqui.com.br
