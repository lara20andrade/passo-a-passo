
 1 - No terminal Git Bash, primeiro entrei na pasta Desktop (Área de Trabalho) usando o comando cd desktop. Em seguida, criei uma nova pasta chamada repositório dentro da Área de Trabalho com o comando mkdir repositório. Depois disso, entrei nessa pasta recém-criada usando o comando cd repositório. Esses comandos serviram para preparar o ambiente onde vou trabalhar com o Git — ou seja, dentro da pasta “repositório”, poderei iniciar um repositório local, clonar um repositório do GitHub ou começar a salvar meus arquivos de projeto.

<img width="349" height="130" alt="image" src="https://github.com/user-attachments/assets/4f58098f-de81-4f4d-bf06-6990225602b0" />



2 - No terminal Git Bash, dentro da pasta repositório, usei o comando
git clone https://github.com/lara20andrade/git-commands.git.

Esse comando serve para clonar (baixar uma cópia completa) de um repositório que está no GitHub para o meu computador. Assim, todos os arquivos, pastas e histórico de commits do repositório git-commands foram copiados para dentro da minha pasta local.

Durante o processo, o terminal mostrou mensagens de progresso, como “Enumerating objects”, “Counting objects” e “Receiving objects”, indicando que os arquivos estavam sendo baixados e organizados.

Ao final, apareceu a mensagem “Resolving deltas: 100%, done”, confirmando que a clonagem foi concluída com sucesso.
Isso significa que agora eu tenho uma cópia completa do repositório git-commands no meu computador, pronta para ser acessada e modificada localmente.

<img width="509" height="166" alt="image" src="https://github.com/user-attachments/assets/cb4ee37e-4ab2-4dc1-917c-c0fa8acedae2" />



3 - No terminal Git Bash, primeiro usei o comando
cd git-commands
para entrar na pasta do repositório clonado. Essa pasta contém todos os arquivos e configurações do projeto que foram baixados do GitHub.

Em seguida, utilizei o comando
git checkout -b documentacao-colaboracao.
Esse comando cria uma nova branch (ramificação) chamada documentacao-colaboracao e já muda para ela automaticamente.

A mensagem “Switched to a new branch 'documentacao-colaboracao'” confirma que a nova branch foi criada com sucesso e que agora estou trabalhando nela.

<img width="557" height="175" alt="image" src="https://github.com/user-attachments/assets/1d98ae05-cd86-4d04-9685-5142a044a06a" />

No terminal Git Bash, dentro do repositório git-commands e na branch documentacao-colaboracao, usei o comando:
git push -u origin documentacao-colaboracao.

<img width="705" height="169" alt="image" src="https://github.com/user-attachments/assets/0405c562-2bd8-43b5-8239-0fd378e45ada" />



4 - No terminal Git Bash, usei o comando
git clone https://github.com/lara20andrade/git-local.git
para clonar o repositório remoto “git-local” do GitHub para o meu computador.

Esse comando criou uma cópia completa do repositório dentro da minha pasta Desktop, incluindo todos os arquivos e histórico de commits existentes.
Durante o processo, o terminal exibiu mensagens como “Enumerating objects”, “Counting objects” e “Receiving objects”, mostrando que o Git estava baixando e organizando os dados.

Em seguida, usei o comando
cd git-local/
para entrar dentro da pasta do repositório clonado, onde posso visualizar, editar arquivos e executar comandos Git locais, como add, commit, branch, ou push.


<img width="444" height="164" alt="image" src="https://github.com/user-attachments/assets/ed65e21e-0c80-4626-81d2-6ff5481b00b5" />



5 - No terminal Git Bash, dentro da pasta do repositório git-local, usei o comando
git checkout -b documentacao-colaboracao.

<img width="539" height="55" alt="image" src="https://github.com/user-attachments/assets/199a88de-5aeb-4cff-a87b-3203bfbcad36" />

A mensagem “Switched to a new branch 'documentacao-colaboracao'” confirma que a nova branch foi criada com sucesso e que agora estou trabalhando nela.

<img width="653" height="132" alt="image" src="https://github.com/user-attachments/assets/78988228-388c-49f0-90dd-0d2fe59528a6" />




6 - No terminal Git Bash, dentro da branch documentacao-colaboracao do repositório git-local, usei o comando. 

Como o terminal exibiu a mensagem “Everything up-to-date”, isso significa que não havia nenhuma nova modificação para enviar, pois a branch local já está totalmente sincronizada com a branch remota no GitHub.
<img width="615" height="48" alt="image" src="https://github.com/user-attachments/assets/88c2f34f-9b73-4e55-b9d2-5558ef525a3f" />



7 - E por fim compartilhei com meus amigos e fiz o passo a passo.
<img width="1583" height="835" alt="image" src="https://github.com/user-attachments/assets/1a31493e-4981-4de7-b85b-cf4a0156802e" />
