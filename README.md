<h1 align='center'>
Introdução ao Git/Github
</h1>

A pedido de amigos escrevi esse tutorial bem básico de como utilizar o git/github. Irei apresentar os principais comandos além de mostrar o passo a passo para ta intalando/configurando o git em sua máquina.

---

# 🔎Onde Instalar:
Para fazer a instalação do git em sua máquina basta acessar o seguinte link: </br>
[![Git](https://img.shields.io/badge/Git-f05032?style=for-the-badge&logo=git&logoColor=white)](https://git-scm.com/downloads)</br>

---

# 🛠️Principais comandos GIT:

## 🙋Setar usuário e email:
Primeiramente, temos que dizer quem será o autor dos commits feitos, para isso devemos utilizar os seguintes comandos para setar usuário e email:
#### 📍git config --global user.name "O seu nome"
#### 📍git config --global user.email o_seu_email@exemplo.com.br
Esses dois comandos serão feitos apenas uma vez para setar as suas informações, caso queira alterar algo basta utilizar-los novamente.  </br>
E se você desejar ver as configurações e checar se estão corretas basta utilizar o comando:
#### 📍git config --list

---

## 👩‍💻Criando um repositório
Se você quise fazer o versionamento de arquivos localmente ou criar um repositório local pra depois deixa-lo remoto basta usar o comando:
#### 📍git init
para vincular esse repósitorio local a um repositório remoto criado no github basta usar:
#### 📍git remote add origin link.do.repositorio
Em seguida usar o:
#### 📍git branch -M main
para renomear a branch:
#### 📍git push -u origin main
para fazer o primeiro upload no repositório remoto.

---

## ⚙️Manutenção de repositório já criado
Verificar o status dos arquivos  no repositório (se estão adicionados ou não)
#### 📍git status

Para ver as diferenças explicitamente basta usar:
#### 📍git diff
---

Para adicionar as mudanças existem comandos difrentes:

#### 📍git add nome_do_arquivo
para adiciona somente um arquivo
#### 📍git add .
para adicionar tudo de uma vez

---

Para "assinar" as mudanças feitas basta utilizar o comando:
#### 📍git commit -m "mensagem relatando as mudanças"

Para subir os commits para a nuvem:
#### 📍git push

Para baixar as diferenças que estão na nuvem:
#### 📍git pull

---

Para ver todos os commits feitos durante a vida do repositório use:
#### 📍git log

---

• Criar e mudar para uma nova branch: git checkout -b nome-da-branch
• Listar as branches existentes: git branch
• Mudar de uma branch para outra: git checkout nome-da-branch
• Juntar as alterações na versão principal: git merge nome-da-branch







