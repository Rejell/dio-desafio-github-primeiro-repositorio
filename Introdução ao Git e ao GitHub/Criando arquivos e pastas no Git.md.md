### Para criar diretórios e/ou arquivos, deve-se seguir os passos abaixo:

1. Abrir o Git Bash (clicar com o botão direito do mouse sobre o diretório raiz) no diretório onde os arquivos e/ou diretórios serão criados;
2. mkdir nome-pasta _--> para criar a pasta com o nome desejado;_
3. git add nome-pasta _--> para mover o diretório do status untraked para o status stage;_
3. echo > README.md _--> para criar arquivo markdown README;_
4. echo texto > arquivo.extensão _--> insere o novo conteúdo (texto) no arquivo criado ou existente (arquivo.extensão);_
5. git add * _--> para mover os dados do status untraked para o status stage;_
6. git commit -m "cria diretório e arquivo" _--> para mover os dados do status stage para o status unmodified_
7. git status _--> para visualizar o status dos arquivos._

### Para mover arquivos de um diretório para o outro, veja os passos a seguir:

 - ls _--> para exibir os arquivos contidos nessa pasta;_
 - mv nome-arquivo ./nome-pasta/ _--> para pover o arquivos da pasta atual para a pasta referida no comando;_
 - git status _--> para visualizar o status dos arquivos;_
 - git add * _--> para mover os dados do status untraked para o status stage;_
 - git commit -m "move arquivo para outro diretório" _--> para mover os dados do status stage para o status unmodified_
 - git status _--> para visualizar o status dos arquivos._