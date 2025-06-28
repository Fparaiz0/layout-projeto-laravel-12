## Como rodar o projeto baixado

Instalar todas as dependências indicadas no package.json.
```
npm install
```

## Sequência para criar o projeto    

Criar o projeto com Tailwind. 
```
npm install tailwindcss @tailwindcss/cli
```

Executar o projeto, gerar a build do css. 
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

Instalar a extensão Live Server no VS CODE.<br>

Clicar sobre o arquivo "index.html" que deve ser aberto "Open with Live Server" ou abrir o arquivo no editor e utilizar ATL + L ou ATL + O.<br>
Será aberto o endereço: http://127.0.0.1:5500/src/index.html

## Como enviar e baixar os arquivos do GitHub 

Criar o repositório "layout-projeto-laravel-12" no GitHub. 
Criar a branch "develop" no repositório. 

Baixar os arquivos do Git. 
```
git clone -b <branch_name> <repository_url> . 
```

Verificar em qual branch o projeto está. 
```
git branch
```

Baixar as atualizações do GitHub.
```
git pull
```

Adicionar todos os arquivos modificados no staging area 
```
git add . 
```