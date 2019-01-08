# Git para principiantes

Vamos começar a série "**Yet Another Tutorial**". Para hoje, que tal aprender um pouco mais sobre um software que orbita a vida de (quase) todo programador.

### **Git, the stupid content tracker.**

Para quem não sabe, **Git** é um software de versionamento. Em outras palavras, é uma ferramenta colaborativa para acompanhar todo tipo de mudança que ocorrer num arquivo contendo o código-fonte seja lá do que for.

Ainda que você prefira, isoladamente, escrever o seu código, pode ser extremamente útil que você tenha o seu código-fonte hospedado em alguma plataforma de preferência. Cada uma tem um sabor peculiar, mas você não precisa se manter fiel apenas a um sabor. Se tudo o que você quer é ter um repositório privado, ***go get it***. Aproveite do melhor que elas tem a oferecer quando e como quiser.

Profissionalmente, aprender a trabalhar em equipe é essencial. Nessa circunstância, o Git se faz muito necessário. Suponhamos que você queira escrever um programa de computador e precisa compartilhar o código com mais algumas pessoas que fazem parte de tal iniciativa. Vocês precisam de organização para que cada um possa ficar incubido de determinada tarefa. Alguns ficarão responsáveis pelo ***back-end***, por exemplo. Outros terão que lidar apenas com o ***front-end***. Etc.

Enfim, enquanto todos estiverem cientes do rumo que os códigos, como um todo, está tomando, torna-se fácil acompanhar o desenvolvimento coletivo de algo que tem o potencial para impactar o meio social -- *sem querer entrar no mérito da discussão, mas softwares precisam ser escritos com consciência moral.*

Vamos colocar a mão na massa!

## Setup e configuração

1. Baixe o instalador do Git em https://git-scm.com/downloads
2. Instale em seu sistema operacional
3. Continue lendo esta instrução



### Uma breve introdução aos interpretadores de comandos

Geralmente, um sistema operacional oferece suporte para que o usuário possa interagir diretamente com o seu sistema através da execução de comandos. No Windows 10, por exemplo, o usuário tem à sua disposição o ***PowerShell***, substituindo o antigo ***Prompt de Comando***. Para linux, temos o famoso Bash; já para Mac OS, há o Terminal.

No início da sua jornada, é preciso ter em mente que:

- Através de um comando, você invoca a execução de algum programa em seu sistema operacional.
- Dependendo do comando, é necessário que você saiba adicionar o respectivo argumento(s) para que o programa saiba onde, quando e/ou o que fazer. As possibilidades são muitas!
- **Flags** são usadas para especificar opções nos diversos comandos encontrados em softwares para linha de comandos, também conhecidos como **CLI** (*Command-line Interface*).



### Um pouco de sintaxe

Com o seu interpretador de comando aberto, a sintaxe básica para usar uma linha de comando, no nosso caso, é a seguinte:

`PS C:\Users\username> git`

A resposta do interpretador será parecida com a seguinte:

#### Como usar:

- `[--version]`
- `[--help]`
- `[-C <path>]`
- `[-c <name>=<value>]`
- `[--exec-path[=<path>]]`
- `[--html-path]`
- `[--man-path]`
- `[--info-path]`
- `[-p | --paginate | -P | --no-pager]`
- `[--no-replace-objects]`
- `[--bare]`
- `[--git-dir=<path>]`
- `[--work-tree=<path>]`
- `[--namespace=<name>]`
- `<command> [<args>]`

Por exemplo:

`git --version`

Alguns comandos usados em várias situações:

### Iniciando uma área de trabalho 


| Comando        | O que faz |
|----------------|-----------|
| clone          | Clone a repository into a new directory |
| init           | Create an empty Git repository or reinitialize an existing one |


### Trabalhando numa mudança atual


| Comando        | O que faz |
|----------------|-----------|
| add            |  Add file contents to the index |
| mv             | Move or rename a file, a directory, or a symlink |
| reset          | Reset current HEAD to the specified state |
| rm 	         | Remove files from the working tree and from the index |

### Examine o histórico e o estado 


| Comando        | o que faz |
|----------------|-----------|
| bisect         | Use binary search to find the commit that introduced a bug |
| grep           | Print lines matching a pattern |
| log            | Show commit logs |
| show           | Show various types of objects |
| status         | Show the working tree status |


### grow, mark and tweak your common history


| Comando        | O que faz |
|----------------|-----------|
| branch         | List, create, or delete branches |
| checkout       | Switch branches or restore working tree files |
| commit         | Record changes to the repository |
| diff           | Show changes between commits, commit and working tree, etc |
| merge          | Join two or more development histories together |
| rebase         | Reaplly commits on top of another base tip |
| tag          | Create, list, delete or verify a tag object signed with GPG |


### Colabore (Veja também: git help workflows)


| Comando        | O que faz |
|----------------|-----------|
| fetch          | Download objects and refs from another repository |
| pull           | Fetch from and integrate with another repository or a local branch |
| push           | Update remote refs along with associated objects |


### Detalhes adicionais

`git help -a` e `git help -g`' retornarão subcomandos disponíveis e alguns guias conceituais. Veja também `git help <comando>` ou `git help <conceito>` para ler sobre um específico subcomando ou conceito.



***Obs***.: Criar tabelas com ***Markdown*** é a coisa mais non-aesthetic que eu já fiz. Enfim, futuras edições serão feitas, bem como a tradução do conteúdo em inglês. Outra alteração

`