## Projeto final da Aula de IAC. 

## Atividades necessárias:


  1 - Subir o ambiente com Vagrant. Os arquivos necessários estão na raiz do git. (VagrantFile, server.sh e iaac.sh)
  
  2 - Realizar a troca de chaves SSH copiando a o conteúdo de id_ra.pub para o server no usuário vagrant.
  
  3 - Baixar o playbook no diretório /vagrant dentro do servidor iaac. (O Playbook em sí está dentro do diretório projeto_iaac, ou seja o playbook deve ser executado a partir deste diretório)
    
  4 - Executar o playbook
  
  5 - Ao executar o playbook a primeira vez você irá observar que a tarefa que valida o status da aplicação vai falhar, porém ao executar a segunda vez ele mostra a aplicação como runnig. 
  
OBS: Para certificar o que o playbook funcionou acesse http://localhost:8000/docs para testar a aplicação. Para acessar o mondo-express acesse http://localhost:8081/
