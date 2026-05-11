# Treinamento Git e GitHub

## Sobre mim
Oie! Meu nome é Ana e estou fazendo o curso disponibilizado pelos QAs da Natura para nos aprofundarmos em automação de testes. Espero gostar mais de automação agora do que da última vez que estudei. ^^
---

# Dicionário Git do QA

| Termo | Significado |
|--------|-------------|
| git init | inicializa um repositório git vazio. após usar esse comando é possível usar os demais comandos;
| git add + nome do arquivo | manda o arquivo específico para staging;
| git add . | manda todos os arquivos para staging;
| git status | mostra o estado atual do repositório, por exemplo mostra as mudanças a serem commitadas;
| git commit -m "mensagem do commit" | salva localmente uma nova versão das alterações que estavam em staging. o commit cria um “checkpoint” do que foi alterado no repositório local;
| git branch -M "main" | renomeia a branch;
| git remote add origin https://github.com/anahauberts/git-and-github-ana-silva-compass.git | cria conexão entre o repositório local com o repositório do github *usar pra colar no terminal ctrl shift v ou insert;
| git push -u origin main | envia a branch main local para o repositório remoto e cria um vinculo entre elas;
| git push origin main ou git push origin "nome-da-branch" | depois de criar a conexão não é mais necessário usar o -u;
| git checkout -b "nome-da-nova-branch" | comando pra criar nova branch, com checkout já muda direto pra essa nova branch;
| git checkout main | muda para a branch principal;
| git merge "nome-da-branch" | para juntar a branch. vai pegar tudo que foi feito na branch "nome-da-branch" e trazer para a branch que vai receber as alterações.
| git pull | serve pra puxar os arquivos do repositório remoto para o local.

# Comandos Favoritos

```bash
git add .
git commit -m "feat: adiciona README"
git push origin main
```
