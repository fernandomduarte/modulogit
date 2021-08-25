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
- adicionando todos os arquivos             -> git add
- salvando as alterações                    -> git commit -m "Comentários sobre as alterações"

Criado o arquivo index.html
Criado o arquivo style.css

Aula 06 - Revertendo modificações
- mostrando todas as alterações           -> git log
- mostrando o BRANCH                      -> git branch
- voltando a um estado anterior ao commit -> git reset --soft id_commit
- voltando ao commit anterior             -> git reset --hard id_commit

Aula 07 - Trabalhando com outros Branchs
- criando um novo branch -> git branch nome_da_versao
- alternando entre branchs -> git checkout nome_da_versao