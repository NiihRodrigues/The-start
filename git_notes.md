# Anotações de Git e Github  
**Comandos básicos**
* git init: Torna o repositório de execução do comando, em um repositório git vazio.

* git add -arquivo-: Faz com que o arquivo seja colocado em uma área de espera, apenas aguardando o próximo comando.  
-> git add.: Adiciona todos os arquivos que ainda não foram.  
-> git add -nome do diretório-: Adiciona im diretório inteiro.  

* git commit -m "titulo do commit": Gravar as mudanças feitas no repositório com uma mensagem, assim ajudando a encontrar mais rápido determinada alteração no projeto. 

* git branch -M "novo nome da branch": Altera o nome da branch que você está.   
-> git branch -a: Moatra todas as branchs locais e remotas.  
-> git branch -delete -nome da branch-: Deleta a branch.

* git status: Mostra o status do repósitório local, como, arquivos que ainda não foram comitados. 

* git remote add origin -link-: Cria a conexão do repositório local com o repositório do link.

* git push -u origin main: É o empurrão que damos nos arquivos comitados no repositório local para o do link.   
-> "origin": Apelido que damos para o repositório.  
-> "main": Branch que queremos empurrar.  

**Outros comandos**
* git checkout -nome da branch-: Sai da branch que está e vai para outra.  
-> git checkout -b -nome da branch-: Cria a branch e entra nela.

* git merge: Junta a branch criada na principal.

* git clone -link-: Clona o repositório do link.

* git pull: Atualiza o reposiŕio que você clonou, assim, adicionando as alterações que ocorreram no link ao repositório local.

**Recursos do github**
* Fork: Faz com que o repositório de alguém seja clonado para os seus repositórios do Github.

* Pull request: Funciona como um pedido de alteração, quando você altera algo na publicação de alguém, para a alteração ser feita no repositório original o dono deve aceitar o pull request.
