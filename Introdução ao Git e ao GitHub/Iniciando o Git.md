### **Link para download do Git: https://gitforwindows.org/**
### _O Git Bash é um terminal extendido para otimizar o uso ao Git._

Após o _download_ e a instalação do Git, abrir o _Git Bash Here_ clicando com o botão direito sobre o diretório de armazenamento Git. Posteriormente, seguir a lista de comandos abaixo para iniciar os trabalhos no Git.
1. git init _--> para inicira o Git;_
2. ls -a _--> para mostrar os arquivos ocultos nesse diretório;_
3. cd .git/ _--> para acessar a pasta Git;_
4. ls _--> para exibir os arquivos contidos nessa pasta;_
5. cd .. _--> para retornar ao diretório anterior;_
6. git config --global user.email "email" _--> inserir o mesmo e-mail cadastrado no GitHub para evitar conflitos;_
7. git config --global user.name "nome" _--> inserir o mesmo nome de usuário cadastrado no GitHub;_
8. git config --list _--> para exibir a lista de configurações na máquina;_
9. git add * _--> para mover os dados do status untraked para o status stage;_
10. git commit -m "commit inicial" _--> para mover os dados do status stage para o status unmodified._ 

Caso deseje alterar o email e/ou o nome nas configurações, basta seguir os comando abaixo:
 - git config --list _--> para exibir a lista de configurações na máquina;_
 - git config --global --unset user.email _--> para deletar o email anteriromente cadastrado;_
 - git config --global --unset user.name _--> para deletar o nome anteriromente cadastrado;_
 - git config --list _--> para exibir a lista de configurações na máquina;_
 - git config --global user.email "email" _--> inserir o mesmo e-mail cadastrado no GitHub para evitar conflitos;_
 - git config --global user.name "nome" _--> inserir o mesmo nome de usuário cadastrado no GitHub;_
 - git config --list _--> para exibir a lista de configurações na máquina._