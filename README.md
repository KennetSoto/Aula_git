# Aula_git

### Comandos GIT

1. `git init`: Inicializa um novo repositório Git vazio no diretório atual ou no diretório especificado como parâmetro.

2. `git config --local user.name "nome_do_usuário"`: Define o nome do usuário local para as configurações do Git. Isso é importante para que o autor do commit possa ser identificado.

3. `git config --local user.email "email_do_usuário"`: Define o endereço de e-mail do usuário local para as configurações do Git. Isso é importante para que o autor do commit possa ser identificado.

4. `git branch <nome_da_nova_branch>`: Cria uma nova branch com o nome especificado.

5. `git branch -M <nome>`: Cria e muda para a nova branch com o nome especificado. O "M" maiúsculo significa "move" e é usado para renomear uma branch existente, enquanto o "m" minúsculo significa "message" e é usado para uma mensagem de commit.

6. `git checkout <nome_do_ramo>`: Troca para a branch especificada.

7. `git add .`: Adiciona todos os arquivos modificados, excluídos ou adicionados ao diretório atual à área de stage do Git para serem incluídos no próximo commit.

8. `git commit -m "mensagem de commit"`: Cria um novo commit com as alterações feitas na área de stage, juntamente com uma mensagem de commit.

9. `git merge <nome_da_branch>`: Mescla as alterações na branch especificada com a branch atual.

10. `git branch -d <nome_da_branch>`: Exclui a branch especificada.

11. `git pull`: Atualiza o repositório local com as alterações feitas no repositório remoto.

12. `git reset HEAD <nome_do_arquivo>`: Remove o arquivo especificado da área de stage do Git.

13. Para sair de um erro ':' aperte q ou q + Enter, tambem funciona ": + x" e Enter para sair.

14. `git revert <número_do_commit>`: Reverte as alterações feitas no commit especificado.

15. `git tag -a <versão> -m <mensagem>`: Cria uma tag para a versão especificada com uma mensagem descritiva.

16. `git push -u origin <main>`: Empurra os commits para a branch principal do repositório remoto.

17. `git tag -a <versão> -m <mensagem>`: Cria uma tag para a versão especificada com uma mensagem descritiva.

18. `git tag -a v0.1 -m "versão"`: Exemplo de criação de tag para a versão 0.1.
     A tag serve para disponibilizar todo o código para ser baixado, zipado ou tar.gz.

19. `git push -u origin <versão>`: Empurra a tag para o repositório remoto.

20. `git clone <caminho_do_repositório> <diretório_de_destino>`: Clona um repositório remoto no diretório de destino especificado.
