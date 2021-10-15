# Comandos usados no Git Bash :desktop_computer:

## Lista de comandos utilizados durante os cursos de Git / GitHub na DIO

- **git config --global user.name "username"**

  *Seta o nome do usuário nas configurações (arquivo config) do git*

- **git config --global user.email "user_email@gmail.com"**

  *Seta o email do usuário nas configurações (arquivo config) do git*

- **git config --global core.editor sub**

  *Associa editor de texto "Sublime Text" ao Git*

- **git config user.name**

  *Retorna o nome do usuário cadastrado no git*

- **git config user.email**

  *Retorna o email do usuário cadastrado no git*

- **git config --list**

  *Lista as informações registradas nas configurações do Git*

- **mkdir 'Nome_do_diretorio'**

  *Cria um diretório na pasta atual*

- **rm -rf './caminho_e_/Nome_do_diretorio/'**

  *Deleta arquivo/diretorio especificado*

- **cd './caminho_e_/Nome_do_diretorio/'**

  *Acessa o interior de uma pasta*

- **git init**

  *Inicializa as configurações do git ou cria um novo repositório do Git*

- **ls**

  *Lista os arquivos/diretórios do diretório atual ou do diretório apontado por um caminho*

- **ls -la**

  *Lista os arquivos/diretórios (incluindo os ocultos) do diretório atual ou do diretório apontado por um caminho*

- **cd ..**

  *Acessa o diretório "pai" do diretório atual*

- **git status**

  *Verifica quais os estados que os arquivos estão. Se existe no repositório algum arquivo modificado, adiciona ou removido.*

- **git add "Nome_Arquivo.ext"**

  *Adiciona qualquer alteração de arquivo ao INDEX do git (staged)*

- **git commit -m "mensagem referente ao estado das alterações"**

  *Captura o estado de um projeto naquele momento*

- **git log**

  *Exibe o que vem sendo feito em uma determinada branch*

- **git log --decorate**

  *Exibe o que vem sendo feito em uma determinada branch exibindo os nomes das refs de quaisquer commits que estão sendo exibidos*

- **git log --author="Will"**

  **Exibe o que vem sendo feito em uma determinada branch exibindo os commits de um autor específico*

- **git shortlog** **e git shortlog -sn**

  *Resume a saída do comando git log*

- **git log --graph**

  *Exibe uma representação gráfica com base no texto do histórico dos commits*

- **git show 4da33... **

  *Exibe informações detalhadas sobre o commit referenciado pela hash passada/solicitada*

- **clear /cls**

  *Limpa o terminal*

- **git diff**

  *Exibe todas as diferenças entre sua cópia local e o índice sincronizado*

- **git diff –cached**

  *Exibe todas as diferenças entre o índice sincronizado e o último commit*

- **git diff HEAD**

  *Exibe todas as diferenças entre sua cópia local e o último commit realizado*

- **git commit -am "Mensagem sobre o commit"**

  *Faz o commit apenas dos arquivos modificados e que encontram-se adicionados na área de stage do Git*

- **git checkout 'Nomedoarquivo.ext**'

  *Além de mudar de branch, o **git checkout** pode ser usado para voltar um determinado arquivo para seu estado na staged area.*

- **git reset HEAD 'NomedoArquivo.txt'**

  *Desfaz as alterações do índice de staging*

- **git reset --soft 5f7e498...**

  *Move apenas o ponteiro HEAD para o commit especificado, sem alterar a área de stage ou o diretório de working*

- **git reset --mixed 5f7e498...**

  *Além de mover o ponteiro HEAD, faz com que a área de stage contenha o mesmo snapshot do commit para o qual o ponteiro HEAD foi movido, porém não afeta o diretório de working.*

- **git reset --hard 5f7e498...**

  *Não apenas descarta as alterações na área de stage como também reverte todas as alterações no diretório de working para o estado do commit que foi especificado no comando*

- **pwd**

  *Exibe o caminho absoluto do diretório atual*

- **git clone git@github.com:username/project_xyz.git**

  *(Clone com SSH) Usado para apontar para um repositório existente e fazer um clone ou cópia deste repositório no novo diretório, em outro local*

- **history**

  *Exibe o histórico de comandos executados no Git Bash*

- **git remote add origin https://github.com/user_name/project.git**

  *Cria uma cópia local de um repositório central, oferecendo uma maneira fácil de enviar pull de alterações de upstream ou publicar commits locais*

- **git remote -v**

  *Mostra URLs de repositórios remotos ao listar suas conexões remotas atuais.*

- **git push origin master**

  *Envia todos os commits no branch local atualmente verificado para o repositório remoto identificado pelo nome origin (no branch remoto nomeado master).*

- **git pull origin master**

  *Fazer um merge: Irá puxar/baixar as alterações da origin master do branch armazenado localmente (repositório remoto) e mesclá-los com o branch com check-out local.*

