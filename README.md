# GIT E GITHUB
Guia prático para iniciantes.

# Instalação
https://git-scm.com/download

# Sua Identidade
A primeira coisa que você deve fazer ao instalar Git é configurar seu nome de usuário e endereço de e-mail. Isto é importante porque cada commit usa esta informação, e ela é carimbada de forma imutável nos commits que você começa a criar:

* `git config --global user.name "Fulano de Tal"`
* `git config --global user.email fulanodetal@exemplo.br`

Reiterando, você precisará fazer isso somente uma vez se tiver usado a opção --global, porque então o Git usará esta informação para qualquer coisa que você fizer naquele sistema. Se você quiser substituir essa informação com nome diferente para um projeto específico, você pode rodar o comando sem a opção --global dentro daquele projeto.

# SCENES

 - [x] Você deseja criar pontos na história da produção do seu projeto

 - [x] Você deseja verificar mudanças feitas no seu projeto

 - [x] Você começa uma nova funcionalidade no seu projeto, sem estragar o que já foi feito.

 - [x] Você adiciona as novas funcionalidades ao seu projeto em produção

 - [x]  Você quer deletar a branch da nova funcionalidade, depois de aplicar em seu projeto.

 - [x] Você quer colocar seu projeto na nuvem.

 - [x] Você vai pegar um projeto já iniciado, para trabalhar com o time

 - [x] Você precisa resolver um conflito.

 - [x] Antes de enviar a resolução, precisamos atualizar o projeto local.

 - [x] Você precisa voltar um arquivo para um determinado momento da linha do tempo.

 - [x] Você precisa recuperar algo deletado.

* `git init` // inicia a linha do tempo
* `git add`  // adiciona ou atualiza mudanças para irem para a linha do tempo
* `git add .` // adiciona ou atualiza todas as mudanças para irem para a linha do tempo
* `git commit -m "Nome"` // adiciona um ponto na linha do tempo
* `git log` // visualiza os pontos na linha do tempo (commit) 
* `git status` // informa o estado das alterações do nosso projeto
* `git show` // apresenta determinado ponto na história
* `git branch` // gerenciar novas linhas do tempo
* `git branch -D nome_da_branch`// deletar uma branch (Ramificação)
* `git checkout` // manipula as linhas do tempo
* `git merge`// unir linhas do tempo
* `git push` // envia alterações locais para o repositório remoto
* `git clone` // clonar um projeto / repositório
* `git pull` // puxa do repositório remoto
