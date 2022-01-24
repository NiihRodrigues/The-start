# Anotações de git  
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

