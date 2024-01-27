"# frontend-fundamentos" 

Utilizando o GitHub - TEM QUE TER O GIT BAIXADO

Criar um novo repositório via github.com

usar sugestão de criação de um novo projeto:

1.
Acessar a pasta desejada:
cd \Users\malum\......
Ou criar uma nova
mkdir caminho-e-nome-da-pasta
cd caminho-e-nome-da-pasta

2.
Criação do arquivo readme
echo '#nome-do-diretorio' >> README.md

3.
Inicialização do monitoramento de mudanças do arquivo
git init

4.
Transferir o arquivo de Changes para Stagged Changes - mandar pro Git Remoto
git add README.md

5.
Realização do primeiro commit
git commit -m "first commit"

6.
Mudar o nome da branch para main
git branch -M main

7.
Sincronia do Git com o GitHub
git remote add origin ~link específico para sua pasta no GitHub~

8.
Mandar os pacotes da máquina para a pasta remota no GitHub
git push -u origin main

9.
Atualizar o site

Outros comandos:

Adicionar todos os arquivos da pasta em Stagged Changes
git add.

Se tiverem alterações realizadas no editor online do GitHub
Para puxar elas para a máquina
git pull

Visualizar os pacotes (autor, data, o que foi feito)
git log

inserir o nome e email no projeto
git config --global user.email = usuárioGitHub.e-mailDesejado

Visualizar a sincronia dos arquivos online e na máquina
Como mudanças não staged
git status

Fluxo do dia a dia

1. Fazer alterações no arquivo
2. git add.
3. git commit -m "Informações que você quer passar"
4. git pull
5. git pull