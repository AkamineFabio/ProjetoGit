Este projeto tem como objetivo praticar a ferramenta git. O intuito é atualizar esse projeto como se fosse um time em que cada pessoa trabalha em um conteúdo do projeto

- abrir o prompt de comando dentro da pasta do projeto

- 'git init' dentro da pasta para inicializar o git
- a pasta atual será a branch master
- 'git add nomedoarquivo' é uma preparação para o commit, deixa o arquivo em uma area de "espera" para quando você der o commit, ele irá ser lançado
- 'git status' para averiguar o status 
- 'git commit -m "titulo para o commit" faz o commit dos arquivos que foram adicionados na espera.
- 'git branch -M "main" para mudar o master para main
- 'git remote add origin link' para colar o link, usar o ctrl+shift+insert
- 'git push -u origin main' para fazer a atualização no github com os commits local que foram feitos 
- origin é um apelido e o push pode ser para main ou master

- 'git add .' adiciona todas as alterações na area de espera
- para criar uma branch, primeiro cria a branch no git para depois alterar o arquivo ou adicionar as mudanças
- 'git checkout -b 'nome-da-branch'' faz com que se crie a branch e mude seu local do master ou main para essa branch
- 'git add .' para adicionar as alterações na espera
- 'git commit -m 'nomedabranch' para confirmar as alterações e commitar 
- 'git push origin nomedabranch' para fazer a branch no repositório do github e mostrar as alterações na branch
- depois de commitar e dar o push, agora é preciso dar merge, para que a alteração feita com a branch seja aplicada na master/main
- 'git checkout main' para mudar para a main novamente 
- 'git merge nomedabranch' para juntar a branch com a main
- 'git push origin main' para aplicar a alteração e o merge para o repositorio

