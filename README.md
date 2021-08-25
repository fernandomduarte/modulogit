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
- Gerando um SSH Key -> ssh-keygen -t rsa -b 4096 "your_email@example.com"