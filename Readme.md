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

É comum que em determinada altura do projeto, queiramos criar uma ramificação, como por exemplo um botão novo ou uma nova página. E para isso criamos a "branch" ou ramificação.
O comando é o `git checkout -b "[nova_branch]". Com esse comando já criamos e nos movemos para a nova branch, por isso do checkout.
Não necessáriamente precisamos criar arquivos para essa nova branch, podemos alterar os já existentes e eles somente alterarão dentro dessa branch.
Para enviar os arquivos para o github é a mesma idéia, com uma única diferença na hora do push, pois não estamos mais na origin e sim na "nova_branch". `git push origin nova_branch`.
Eventualmente pode aparecer no github dizendo que a branch está mais atualizada que a main.
    Caso você queira sair da branch e voltar a trabalhar na main é do digitar `git checkout main`.

Quando eu quiser juntar a branch a main, preciso estar trabalhando com a main. `git checkout main`e digitar o comando "merge".
Esse novo comando é o `git merge nova_branch`.
E depois precisamos enviar ao github com o `git push origin main`.

Caso queira copiar um repositorio seja seu ou de terceiros, basta ir ao github e copiar o link e utilizar o seguinte comando `git clone [link_do_repo]`.
E para atualizar o clone,caso você queira verificar se há novas atualizações por exemplo, basta digitar o `git pull`.