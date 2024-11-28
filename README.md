# Insta-Bytes Código Front-End & Back-End

Este é o repositório do projeto.

![Screenshot 2024-11-28 162543](https://github.com/user-attachments/assets/4b296cab-62f8-4144-be3a-d863226a8128)

![Screenshot 2024-11-28 162612](https://github.com/user-attachments/assets/08cf4a76-cdd0-43a7-9287-609bda75e4b9)


**IMPORTANTE:** É necessário ter o [Node.js](https://nodejs.org/) instalado em seu computador antes de executar os comandos de instalação e execução do projeto. Versão recomendada: v20.x.x.
E também é importante que você baixe ou clone o arquivo do Back-end: https://github.com/Loy7g/InstaBytesBackEnd

## PASSO 1: Baixe o código do projeto:

### Opção 1 - Clonando o repositório para o seu perfil no GitHub

> Para utilizar essa opção é necessário ter o [Git](https://git-scm.com/downloads) instalado e configurado em seu computador. Caso não esteja instalado ou você não tenha certeza, prossiga com a **opção 2** e baixe o .zip do projeto.

1. Faça o **fork** do projeto clicando no botão **Fork** na parte superior direita da página;
2. Faça o **clone** do repositório para seu computador:
  - Clique no botão **<> Code** e copie o endereço remoto do repositório;
  - Abra o terminal, navegue até a pasta raiz onde deseja baixar o projeto e execute o comando `git clone <endereço remoto>`;
  - Você pode acessar a pasta do projeto direto pelo Visual Studio Code, clicando em File > Open Folder e selecionando a pasta do projeto.

### Opção 2 - Baixando um arquivo .zip

1. clique no botão **<> Code** e, em seguida, no botão **Download ZIP**;
2. uma pasta zipada será baixada para a pasta de downloads determinada pelo seu navegador;
3. descompacte os arquivos clicando no ícone da pasta zipada e transfira os arquivos para a pasta de projetos de sua preferência.


## PASSO 2: Instale o projeto:

### Opção 1 - Utilizando o terminal do Visual Studio Code

1. Abra a pasta de Back-End do Projeto no Visual Studio Code clicando em File > Open Folder e selecionando a pasta do projeto (Projeto InstaBytes > instaBytesBackEnd ), lembrando que você tem que instalar o back e o front em janelas diferentes e deixar os dois rodando simultaneamente, para isso após abrir a pasta do Back-End, vá em File > New Window > File > Open Folder > Projeto InstaBytes > instaBytesFrontEnd, abrindo assim também a pasta do Front-End em outra janela ao mesmo tempo;
2. Em ambas as janelas, clique em Terminal > New Terminal no menu superior do Visual Studio Code. O terminal deve abrir já direcionando para a pasta correta do projeto e não se esqueça de mudar o terminal para CMD (Command Prompt), (É uma setinhna pra baixo que fica localizado ao lado do botão + na direita do terminal, e ao clicar nela você escolhe o tipo de terminal que precisa ou deseja);
3. Execute o comando `npm install` em ambos e aguarde a finalização.

### Opção 2 - Utilizando outros terminais

1. Abra o terminal de sua preferência e navegue até a pasta do projeto, utilizando os comandos de navegação como `cd <pasta>`;
2. Com o prompt apontando para a raiz da pasta do projeto, execute o comando `npm install` e aguarde a finalização, lembrando de abrir um pra cada pasta, um do Front-End e outro do Back-end.

## PASSO 3: Execute o projeto para subir o servidor local:

### NO ARQUIVO BACK-END: 

Acesse o terminal (do Visual Studio Code ou outro), certifique-se que esteja exibindo a pasta correta do projeto e execute o comando `npm run dev`. O terminal deverá retornar:

> dev
> node --watch --env-file=.env server.js

Conectando ao cluster do banco de dados...
Conectado ao MongoDB Atlas com sucesso!
Servidor escutando...

### NO ARQUIVO FRONT-END:

Acesse o terminal (do Visual Studio Code ou outro), certifique-se que esteja exibindo a pasta correta do projeto e execute o comando `npm run dev`. O terminal deverá retornar:

```
> dev
> npx parcel --port 8000 index.html

Server running at http://localhost:8000
✨ Built in xxxms
```

O projeto estará disponível no endereço http://localhost:8000 e você poderá acessá-lo no navegador de sua preferência.
