<!DOCTYPE html>

<html>

<head>

   <meta charset="UTF-8"/>
   <title>Página principal</title> 

</head>

<body>

   <h1>Conhecendo o Github</h1>

   <p>  <img src= "git.png" > </p>

   <br>

   <h2>Como acessar e usar o Github?</h2>


   <ul>

       <li>O GitHub é gratuito, exigindo apenas um cadastro para utilizar todos os seus recursos. Os projetos são hospedados em “repositórios”, que podem ter acesso público ou privado. Desde a compra pela Microsoft, todos os usuários têm acesso ilimitado a repositórios particulares.O GitHub é gratuito, exigindo apenas um cadastro para utilizar todos os seus recursos. Os projetos são hospedados em “repositórios”, que podem ter acesso público ou privado.</li> 
       
        <li>entre pelo link abaixo e faça sua conta e pronto!</li>

        <li><a href="https://github.com/">Github.com</a></li>
    
   </ul>

   <br>

   <h2><mark>Por que</mark> usar o github?</h2>
   
   <ul>
       <li>Github é utilizados no dia a dia das pessoas que criam softwares por um motivo bem simples: ter uma forma fácil de gerenciar o código-fonte da aplicação, do sistema e do produto.</li>
       <li>Aumento dramático na velociade de operação e Árvore de historico completo disponivel off-line são mais exemplos para o por que de usar o Github.</li> 
       <li>confira um audio mais detalhado cliclando aqui:<a href="projeto-icc/audio.html"> Audio.comandos </a></li>
   </ul>     
   
   
   <h2>Quais são os comandos utilizados no Github?</h2> 
   <h4>Existem diversos,mas confira alguns exemplos:</h4> 
   
   <table>
       <tr>
           <td><b>Init, Clone, Branch</b></td>
       </tr>         
       <tr>
           <td><b>Checkout, Status, Diff</b></td>
       </tr>    
       <tr>
           <td><b>Add, Commit, Push</b></td>
       </tr> 
       <tr>
           <td><b>Pull, Revert, Merge</b></td>
       </tr>         
       <tr>
           <td><b>Stash, Rm, Config</b></td>
       </tr>     
       <tr>
            <td><b>Reset, Remote, Retch</b></td>
       </tr>        
       <tr>
            <td><b>Show, Help, Rebase</b></td>
       </tr>       
       <tr>
            <td><b>Blame, Tag</b></td>
       </tr>
   </table>
   
   <h2>Abaixo há um link para um video com a explicação mais profunda de alguns comandos do Git</h2>
   
   <p><a href="projeto-icc/video.html"> <img src="yt.png"> </a>
   
   
   
   
   <h2>Agora conhecidos vamos ver a descrição,explicação e uso destes comandos:</h2> 
   
   <dl>
       <dt><b>Comando Init:</b></dt>
       <dd><i>Cria um novo repositório Git vazio na pasta atual.</i></dd>
       <dd><i>O comando init é usado para inicializar um novo repositório Git em um diretório. Ele cria um subdiretório oculto chamado ".git" que contém todos os arquivos e metadados necessários para rastrear as alterações do projeto.</i></dd>  
       <dd><i>Uso: Abra o terminal, navegue até o diretório do projeto e execute o comando `git init`.</i>
   </dl>
   <dl>
       <dt><b>Comando Clone:</b></dt>
       <dd><i>Cria uma cópia local de um repositório remoto.</i></dd>
       <dd><i>O comando `clone` é usado para criar uma cópia local de um repositório remoto. Ele copia todos os arquivos, histórico de commits e branches do repositório remoto para o seu computador.</i></dd> 
       <dd><i>Uso: Execute `git clone URL_do_repositório` para clonar um repositório remoto.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Branch:</b></dt>
       <dd><i>Lista, cria ou exclui branches.</i></dd>
       <dd><i>O comando `branch` é usado para listar, criar ou excluir branches (ramificações) em um repositório Git. Branches permitem trabalhar em diferentes versões do projeto simultaneamente.</i></dd> 
       <dd><i>- Uso:
     - Para listar todos os branches: `git branch`.
     - Para criar um novo branch: `git branch nome_do_branch`.
     - Para excluir um branch: `git branch -d nome_do_branch`.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Checkout:</b></dt>
       <dd><i>Alterna entre branches ou restaura arquivos.</i></dd>
       <dd><i>O comando `checkout` é usado para alternar entre branches ou restaurar arquivos em um repositório Git. Ele permite que você trabalhe em diferentes branches ou reverta alterações em arquivos.</i></dd>
       <dd><i>- Uso:
     - Para alternar para um branch específico: `git checkout nome_do_branch`.
     - Para restaurar um arquivo para o estado do último commit: `git checkout -- nome_do_arquivo.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Status:</b></dt>
       <dd><i>Exibe o status atual do repositório.</i></dd>
       <dd><i>O comando `status` é usado para exibir o status atual do repositório Git. Ele mostra informações sobre quais arquivos foram modificados, adicionados ou removidos, e em qual branch você está.</i></dd>
       <dd><i>- Uso: Execute `git status` para ver o status do repositório.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Diff:</b></dt>
       <dd><i>Mostra as diferenças entre commits, branches ou arquivos.</i></dd>
       <dd><i>O comando `diff` é usado para mostrar as diferenças entre commits, branches ou arquivos. Ele mostra as linhas que foram adicionadas, removidas ou modificadas.</i></dd>
       <dd><i>- Uso:
     - Para ver as diferenças entre o último commit e o estado atual: `git diff`.
     - Para ver as diferenças entre dois commits: `git diff commit_A commit_B`.
     - Para ver as diferenças em um arquivo específico: `git diff nome_do_arquivo`.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Add:</b></dt>
       <dd><i>Adiciona arquivos ao index.</i></dd>
       <dd><i>O comando `add` é usado para adicionar arquivos ao index (também conhecido como área de staging) do Git. Isso prepara os arquivos para serem incluídos no próximo commit.</i></dd>
       <dd><i> - Uso:
     - Para adicionar todos os arquivos modificados ao index: `git add .`.
     - Para adicionar um arquivo específico ao index: `git add nome_do_arquivo`.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Commit:</b></dt>
       <dd><i>Grava as alterações no repositório.</i></dd>
       <dd><i>O comando `commit` é usado para gravar as alterações no repositório como um novo commit. Um commit é uma versão do projeto que inclui todas as alterações preparadas no index.</i></dd>
       <dd><i>- Uso: Execute `git commit -m "mensagem_do_commit"` para criar um novo commit.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Push:</b></dt>
       <dd><i>Envia os commits locais para um repositório remoto.</i></dd>
       <dd><i>O comando `push` é usado para enviar os commits locais para um repositório remoto. Ele sincroniza o repositório local com o repositório remoto, tornando as alterações disponíveis para outros colaboradores.</i></dd>
       <dd><i>- Uso: Execute `git push nome_do_remoto nome_do_branch` para enviar os commits para o repositório remoto.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Pull:</b></dt>
       <dd><i>Obtém as alterações do repositório remoto e as mescla com o branch local.</i></dd>
       <dd><i>O comando `pull` é usado para obter as alterações do repositório remoto e mesclá-las com o branch local. É útil para atualizar seu branch com as alterações feitas por outros colaboradores.</i></dd>
       <dd><i>- Uso: Execute `git pull nome_do_remoto nome_do_branch` para obter e mesclar as alterações remotas.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Revert:</b></dt>
       <dd><i>Desfaz um commit específico, criando um novo commit com as alterações revertidas.</i></dd>
       <dd><i>O comando `revert` é usado para desfazer um commit específico, criando um novo commit que desfaz as alterações introduzidas pelo commit original.</i></dd> 
       <dd><i>- Uso: Execute `git revert hash_do_commit` para desfazer um commit específico.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Merge:</b></dt>
       <dd><i>Mescla um branch com outro branch ativo.</i></dd>
       <dd><i> comando `merge` é usado para mesclar um branch com outro branch ativo. Ele combina as alterações dos dois branches, criando um novo commit de mesclagem.</i></dd>
       <dd><i> - Uso: Primeiro, alterne para o branch de destino com `git checkout branch_destino`. Em seguida, execute `git merge branch_a_ser_mesclado` para mesclar o branch desejado.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Stash:</b></dt>
       <dd><i>Salva as alterações locais em um local temporário para que você possa alternar de branch sem fazer um commit.</i></dd>
       <dd><i>O comando `stash` é usado para salvar as alterações locais em um local temporário (stash) para que você possa alternar de branch sem fazer um commit. Isso permite que você retome as alterações mais tarde.</i></dd>
        <dd><i> - Uso:
      - Para salvar as alterações em um stash: `git stash`.
      - Para retomar as alterações salvas em um stash: `git stash apply`.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Rm:</b></dt>
       <dd><i>Remove arquivos do diretório de trabalho e do index.</i></dd>
       <dd><i>O comando `rm` é usado para remover arquivos do diretório de trabalho e do index (área de staging) do Git.</i></dd>
       <dd><i>- Uso: Execute `git rm nome_do_arquivo` para remover um arquivo do diretório de trabalho e do index.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Config:</b></dt>
       <dd><i>Define as configurações do repositório Git.</i></dd>
       <dd><i>O comando `config` é usado para definir as configurações do repositório Git, como nome de usuário, endereço de e-mail, preferências de formatação, etc.</i></dd> 
       <dd><i>- Uso:
      - Para definir o nome de usuário: `git config --global user.name "Seu Nome"`.
      - Para definir o endereço de e-mail: `git config --global user.email "seu-email@example.com"`.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Reset:</b></dt>
       <dd><i>Desfaz alterações, movendo o HEAD e o branch atual para um commit específico.</i></dd>
       <dd><i>O comando `reset` é usado para desfazer alterações, movendo o HEAD e o branch atual para um commit específico. Ele pode ser usado para descartar commits ou desfazer alterações no diretório de trabalho.</i></dd> 
       <dd><i>- Uso:
      - Para descartar as alterações em um arquivo específico: `git reset HEAD nome_do_arquivo`.
      - Para desfazer todos os commits e descartar todas as alterações: `git reset --hard commit`.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Remote:</b></dt>
       <dd><i>Gerencia repositórios remotos vinculados ao seu repositório local.</i></dd>
       <dd><i>O comando `remote` é usado para gerenciar repositórios remotos vinculados ao seu repositório local. Ele permite que você adicione, remova ou liste repositórios remotos.</i></dd> 
       <dd><i> Uso:
      - Para adicionar um repositório remoto: `git remote add nome_do_remoto URL_do_repositório`.
      - Para listar repositórios remotos: `git remote -v`.
      - Para O comando `reset` é usado para desfazer alterações, movendo o HEAD e o branch atual para um commit específico. Ele pode ser usado para descartar commits ou desfazer alterações no diretório de trabalho.remover um repositório remoto: `git remote remove nome_do_remoto`.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Fetch:</b></dt>
       <dd><i>Obtém as alterações do repositório remoto sem mesclá-las com o branch local.</i></dd>
       <dd><i>O comando `fetch` é usado para obter as alterações do repositório remoto sem mesclá-las com o branch local. Ele busca as alterações mais recentes, mas não as aplica automaticamente.</i></dd> 
       <dd><i>- Uso: Execute `git fetch nome_do_remoto` para buscar as alterações do repositório remoto.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Show:</b></dt>
       <dd><i>Exibe informações sobre um commit específico.</i></dd>
       <dd><i>O comando `show` é usado para exibir informações detalhadas sobre um commit específico, como autor, data, mensagem e alterações feitas.</i></dd> 
       <dd><i> - Uso: Execute `git show hash_do_commit` para exibir as informações de um commit específico.</i></dd>
   </dl>
   <dl>
       <dt><b>Comando Help:</b></dt>
       <dd><i>Exibe o manual de ajuda do Git.</i></dd>
       <dd><i>O comando `help` é usado para exibir o manual de ajuda do Git. Ele fornece informações sobre os comandos do Git e sua sintaxe.</i></dd> 
        <dd><i>- Uso: Execute `git help` para ver a documentação de ajuda do Git.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Rebase:</b></dt>
       <dd><i>Aplica os commits de um branch em cima de outro branch.</i></dd>
       <dd><i>O comando `rebase` é usado para aplicar os commits de um branch em cima de outro branch. Ele move ou combina commits de um branch para outro, criando uma linha de tempo linear.</i></dd> 
       <dd><i>- Uso: Primeiro, alterne para o branch de destino com `git checkout branch_destino`. Em seguida, execute `git rebase branch_a_ser_rebasiado` para rebasar o branch desejado.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comand o Blame:</b></dt>
       <dd><i>Mostra quem modificou cada linha de um arquivo e em qual commit.</i></dd>
       <dd><i>O comando `blame` é usado para mostrar quem modificou cada linha de um arquivo e em qual commit a modificação foi feita. Ele ajuda a rastrear a autoria de alterações específicas.</i></dd> 
        <dd><i> Uso: Execute `git blame nome_do_arquivo` para mostrar a autoria das linhas do arquivo.</i></dd> 
   </dl>
   <dl>
       <dt><b>Comando Tag:</b></dt>
       <dd><i>Marca um commit específico com uma etiqueta nomeada.</i></dd>
       <dd><i>O comando `tag` é usado para marcar um commit específico com uma etiqueta nomeada. As tags são usadas para indicar versões estáveis, marcos importantes ou releases do projeto.</i></dd> 
        <dd><i>- Uso:
      - Para criar uma tag leve (apenas um ponteiro para um commit): `git tag nome_da_tag`.
      - Para criar uma tag anotada (inclui informações adicionais, como autor e data): `git tag -a nome_da_tag -m "mensagem_da_tag"`.
      - Para enviar tags para um repositório remoto: `git push nome_do_remoto --tags`.</i></dd>
   </dl>
   
   
</body>

</html>
