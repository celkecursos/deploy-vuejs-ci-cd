Projeto criado durante o tutorial como realizar o deploy do projeto criado com Vue.js.

## Requisitos

* Node.js 22 ou superior - Conferir a versão: node -v
* NPM - Conferir a versão: npm -v
* GIT - Conferir se está instalado o GIT: git -v

## Como rodar o projeto baixado

Instalar as dependências.
```
npm install
```

Compilar e recarregar durante o desenvolvimento.
```
npm run dev
```

Acessar a página criada.
```
http://localhost:5173/
```

## Sequência para criar o projeto

Criar o projeto com Vue.js. O ponto "." no final indica que o projeto será criado no mesmo diretório.
```
npm create vue@latest
```

- Package name: Digitar o nome do projeto.
- Select features to include in your project: Pressione Enter e não selecione nenhuma opção para criar o projeto da forma mais simples possível.
- Select experimental features to include in your project: Pressione Enter, pois não é necessário utilizar recursos experimentais.
- Skip all example code and start with a blank Vue project? Selecione No para começar com um projeto mínimo.

Instalar as dependências.
```
npm install
```

Compilar e recarregar durante o desenvolvimento.
```
npm run dev
```

Acessar a página criada.
```
http://localhost:5173/
```

## Como enviar o projeto para o GitHub.

Inicializar um novo repositorio GIT.
```
git init
```

Adicionar todos os arquivos modificados na área de preparação.
```
git add .
```

Verificar em qual branch está.
```
git branch
```

Commit registra as alterações feitas nos arquivos que foram adicionados na área de preparação.
```
git commit -m "feat: adicionar estrutura base do projeto Vue.js"
```

Renomear a branch atual no GIT para main.
```
git branch -M main
```

Adicionar um repositório remoto ao repositório local.
```
git remote add origin https://github.com/celkecursos/deploy-vuejs-ci-cd.git
```

Enviar os commits locais para um repositório remoto.
```
git push -u origin main
```

## Autor

Este projeto foi desenvolvido por [Cesar Szpak](https://github.com/cesarszpak) e está hospedado no repositório da organização [Celke](https://github.com/celkecursos).

## Licença

Este projeto está licenciado sob a licença MIT - veja o arquivo [LICENSE](LICENSE.txt) para mais detalhes.

