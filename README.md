Curso de GIT

Alguns dos conceitos básicos
- BRANCH versões do projeto
- COMMIT salvando as atualizações do projeto

Aula 04 - Iniando um repositório
-> cd projeto
-> git init

Aula 05 - Branch e Commit
- verificando se há alterações pendentes    -> git status
- adicionando um arquivo para monitoramento -> git add nome do arquivo
- adicionando todos os arquivos             -> git add -A
- salvando as alterações                    -> git commit -m "Comentários sobre as alterações"

Criado o arquivo index.html
Criado o arquivo style.css

Aula 06 - Revertendo modificações
- mostrando todas as alterações           -> git log
- mostrando o BRANCH                      -> git branch
- voltando a um estado anterior ao commit -> git reset --soft id_commit
- voltando ao commit anterior             -> git reset --hard id_commit

Aula 07 - Trabalhando com outros Branchs
- criando um novo branch   -> git branch nome_da_versao
- alternando entre branchs -> git checkout nome_da_versao

Aula 08 - Diferença entre arquivos
- visualizando em detalhes as altarações nos arquivos      -> git diff
- mostrar somente quem quais arquvos houveram modificações -> git diff --name-only
- mostar alterações em um arquivo específico               -> git diff nome_do_arquivo
- desfazer alterações em um arquivo específico             -> git checkout HEAD -- nome_do_arquivo

Aula 09 - Criando um respositorio no site Github

Aula 10 - Conectando um repositório local ao remoto
- Gerando um SSH Key -> ssh-keygen -o -t rsa -C "your@email.com"
- Local onde será salvo o SSH: C:/Users/seunome/.ssh/id_rsa
- Criando o repositório remoto                           -> git remote add origin url_do_repositorio.git
- Verificando Ok                                         -> git remote
- Enviando o projeto existente para o repositorio remoto -> git push -u origin(site oficial do git) master(nome_do_branch)

Aula 11 - Fazendo alterações no repositório remoto
- Enviando o projeto atualizado para o remoto -> git push origin master
