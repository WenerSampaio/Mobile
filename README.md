# Mobile
## Introdução ao Git / GitHub - DIO.ME

### 1) Comandos básicos
* git config --list  --> lista todas as configurações;
* git config --global --unset user.mail --> apaga configuração de email;
* git config --global --unset user.nickname --> apaga configuração de nome de usuário;
* git config --global user.mail "meuemail@mail.com"--> personaliza configuração de email;
* git config --global user.nickname "wenersampaio"--> personaliza configuração de nome do usuário.

### 2) Pra realizar um commit:
* Entrar no github/profile/ --> ver informações importantes do meu perfil;
* Entrar no github/your repositories/new --> cria um novo repositório.
 
#### 2.1) Após criar, copiar o link do repositório
* git remote add origin <link do repositório>;
* git remote -v --> lista todos os meus repositórios;
* git status  --> verifica pendências no repositório;
* git add * --> avisa ao git que existe arquivos modificados;
* git commit -m "Comentário relativo à modificação";
* git push origin master --> envia para o servidor;
* git push -u origin master;
* git pull origin master --> baixa para a máquina local.
 
 
#### 2.2) Para copiar ou clonar um repositório:
* Copiar o *link* https do repositório;
* git clone *link*.