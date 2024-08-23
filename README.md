# avaliacao-jp
Avaliação Senac- 22/08/2024
Comandos do git:

    Primeiramente devemos pesquisar por gitbash em nosso computador. Após isso, vamos realizar a verificação da chave ssh (se ela existe no nosso computador) para isso vamos executar ls - al ~/.ssh, depois disso iremos colocar uma nova chave aplicando: ssh-keygen -t ed25519(chave)-C "luizanicolait59@gmail.com", no caso o seu proprio e-mail, depois vamos finalmente começar a checar a conexão com o ssh com o comando: eval "$(ssh-agente-s)". Se não apareceu nenhuma mensagem de erro podemos colocar a ssh com a chave ed25519 que criamos no comando anterior através de : ssh-add ~/.ssh/id_chave e agora podemos copia-la para então podermos adicionar em seu github com o comando: clip < ~/.ssh/id_chave.pub .
        Em seguida, iremos logar a nossa conta do github em nosso computador, colocar o seu e-mail e a senha, depois é necessário ir na opção Settings que fica no canto direito da tela e encontrara a opção SSH and GPG keys apertar em New SSH key -> e colar a chave que copiamos no terminal, logo apos coloque um titulo que mais se encaixe em suas necessidades. Para finalizar teste a conexão do ssh com o github para ver se deu tudo certo no gitbash com o comando ssh -T git@github.com yes.


        