## Requisitos

* Conferir a versão do Node.js 22 ou superior: node -v
* Conferir se está instalado o GIT: git -v

## Como rodar o projeto baixado

Instalar todas as dependências indicadas no package.json.
```
npm install
```

Executar o projeto e gerar a build do CSS.
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

- Instale a extensão **Live Server** no VS Code.
- Abra o arquivo **"index.html"** com o Live Server.

### Métodos para abrir o Live Server:

1. **Primeira opção:** Pressione `ALT + L` e `ALT + O`.
2. **Segunda opção:** Clique com o botão direito do mouse sobre o arquivo **"index.html"** e selecione **"Open with Live Server"**.

Será aberto o endereço: http://127.0.0.1:5500/src/index.html

## Sequência para criar o projeto

Criar o projeto com Tailwind.
```
npm install tailwindcss @tailwindcss/cli
```

Executar o projeto e gerar a build do CSS.
```
npx @tailwindcss/cli -i ./src/input.css -o ./src/output.css --watch
```

- Instale a extensão **Live Server** no VS Code.
- Abra o arquivo **"index.html"** com o Live Server.

### Métodos para abrir o Live Server:

1. **Primeira opção:** Pressione `ALT + L` e `ALT + O`.
2. **Segunda opção:** Clique com o botão direito do mouse sobre o arquivo **"index.html"** e selecione **"Open with Live Server"**.

Será aberto o endereço: http://127.0.0.1:5500/src/index.html

## Como enviar e baixar os arquivos do GitHub

- Criar o repositório **"layout-adm-tailwind"** no GitHub.
- Criar o branch **"develop"** no repositório.

Baixar os arquivos do Git.
```
git clone -b <branch_name> <repository_url> .
```

Alterar o usuário globalmente "--global" (para todos os repositórios) ou alterar o usuário apenas para um repositório "--local".
```
git config --global user.name "SeuNomeDeUsuario"
git config --global user.email "seuemail@exemplo.com"
```

Verificar em qual está branch.
```
git branch 
```

Baixar as atualizações do GitHub.
```
git pull
```

- Colocar o código fonte do projeto no diretório que está trabalhando.

Adicionar todos os arquivos modificados no staging area - área de preparação.
```
git add .
```

commit representa um conjunto de alterações e um ponto específico da história do seu projeto, registra apenas as alterações adicionadas ao índice de preparação.
O comando -m permite que insira a mensagem de commit diretamente na linha de comando.
```
git commit -m "Base projeto"
```

Enviar os commits locais, para um repositório remoto.
```
git push <remote> <branch>
git push origin develop
```

## Autor

Este projeto foi desenvolvido por [Felipe Paraizo](https://github.com/Fparaiz0) e está hospedado no [repositório](https://github.com/Fparaiz0/layout-projeto-laravel-12/tree/develop).

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE.txt) para mais detalhes.
