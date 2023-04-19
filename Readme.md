# treinando-git-github
Roadmap para começar a utilizar git e github

1 - Inicializar o git/criar um repositorio: Abrir o terminal na pasta que irá ser utilizada e colocar o comando `git init`.
2 - Mandar os arquivos para a área de Stage, que é meio que um lugar para preparar os arquivos até serem salvos de fato. Atraves do comando `git add [nome_do_arquivo]`. Caso queira enviar todos os arquivos da pasta é só digitar `git add . `.
3 - Verificar o status dos arquivos: `git status` com esse comando vemos se já esta tudo comitado ou não.
4 - E por fim, `git commit -m"[coloque_a_descricao_do_commit]".
5 - Verificar com o git status se está tudo atualizado.

6 - Caso queira mudar o nome da "master" para "main", só digitar `git branch M "main".
7 - Agora é linkar o repositorio git com o github. Para isso precisamos criar um repositorio em nosso github e depois linkar eles.
8 - Digite o comando `git remote add origin [link_ssh_ou_https_do_repo].

E agora precisamos enviar os arquivos para o github.

9 - `git push -u origin main` , e ai entrar com a senha e pronto.
