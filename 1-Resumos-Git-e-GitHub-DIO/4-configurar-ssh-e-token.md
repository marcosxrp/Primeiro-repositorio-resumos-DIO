### Chave ssh
- github - new ssh key
- git - ssh-keygen -t ed25519 -C "email" // criando chave ssh, sera exibido o local que sera criado, por padrao /c/users/pichau/.ssh/ mas da pra trocar escrevendo o local desejado
- git - escrever senha
- git - ir no local do arquivo pelo comando cd
- git - cat id_25519.pub tem que ser a chave publica para mostrar para os outros
- git - copia a chave publica gerada
- github - adiciona a chave e salva
- git - eval $(ssh-agent- s) // adicionando e ativando o agente responsavel por lidar com as chaves
- git - ssh-add id_25519 // tem que ser a privada
- git - adicionar senha
### Token
- github - developer settings
- github - new personal acess token
- github - marcar repo
- github - concluir
- github - copiar token e salvar no computador // n sera possivel ver novamente se n salvar
- **token sera pedido quando for clonar algo usando o https**
