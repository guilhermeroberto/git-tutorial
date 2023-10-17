<h1> Git Tutorial </h1>

<h2> #1 - Criando um Projeto </h2>

- Crie um repositório no GitHub

- Crie uma pasta para o projeto no seu PC

- Abra a pasta com o VSCode

- Crie um arquivo README.txt e escreva algo

- Abra o terminal do VSCode

<h2> #2 - Configurando conta </h2>
git config --global user.email "you@example.com"
<br><br>
git config --global user.name "Your Name"

<h2> #3 - Utilizando o Git </h2>

1. Iniciando repositório: `git init`
2. Adicionando arquivos: `git add ./README.md`
3. Executando commit: `git commit -m "Adicionando Readme"`
4. Alterando branch principal: `git branch -M "main"`
5. Entrando no repositório criado: `git push -u origin main LINK`
5. Adicionando todas alterações: `git push origin main`
6. Caso queira encerrar a conexão com o repositório local: `git remote rm origin`