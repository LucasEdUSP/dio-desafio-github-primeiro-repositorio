# Desafio de Projeto sobre Git/GitHub da DIO
Repositório criado para o Desafio de Projeto.

## Links úteis
[Sintaxe Básica Markdown](https://www.markdownguide.org/)

## Como criar um repositório no GitHub:

### Você vai precisar:

 - Instalar o [Git](https://git-scm.com/) no seu computador;
 - Criar uma conta no [GitHub](https://github.com/).

1. Instalando o Git (no Windows):

 - Vá no site do [Git](https://git-scm.com/);
 - Clique em **"Download for (insira o nome do seu sistema operacional aqui)"**;
 - Escolha a versão adequada para o seu sistema operacional (se é 32 ou 64 bits);
 - Feito o donwload, clique para abrir o executável;
 - Durante a instalação, deixe as opções marcadas:
 - [x] Git Bash Here
 - [x] Git GUI Here
 - Como editor padrão do Git, deixe marcada a opção **"VIM"**;
 - Quanto ao nome da branch inicial do git, marque a opção **"Let Git decide"**
 - Na parte de configurar as conversões de final de linha, a primeira opção ("Checkou Windows-style, commit Unix-style line endings") é para os usuários de **Windows**, e a segunda opção ("Checkout as-is, commit Unix-style line endings") são para usuários de **Linux** 🐧;
 - **IMPORTANTE:** Na hora de escolher o credential helper, é necessário selecionar a opção **"Git Credential Manager Core"** para se evitar problemas futuros na hora de realizar operações no Git, pois a opção **"Git Credential Manager"** se trata de uma opção defasada.
 - Após essas ressalvas, pode-se prosseguir com a instalação normalmente.
 - *Et Voilà!*, o Git está instalado!

2. Criando um repositório usando Git:
 
 - Vá no diretório C:/ do seu computador e crie uma pasta chamada `workspace;
 - Dentro dessa pasta, clique com o botão direito do mouse e selecione a opção "Git Bash Here";
 - Na janela que se abrir, digite `cd workspace` para entrar na pasta do workspace;
 - Para criar um repositório, digite `mkdir nome_do_repositório`;
 - Novamente digite `cd nome_do_repositório` para acessar o repositório;
 - Digite `git init` para inicializar um repositório;
 - Caso seja a primeira vez que está usando o git, você vai ter que configurar um usuário, para isso, digite `git config --global user.email "seu email aqui"` após isso digitar a seguinte linha `git config --global user.name seu_nome`;

3. Criando arquivos para o repositório:
 - Dentro da pasta `workspace` crie um arquivo de texto com extensão `.md`.;
 - Crie o arquivo com o texto que desejar;
 - Após isso, vamos adicionar os arquivos digitando `git add *` e `git commit -m "commit inicial"`;

4. Lidando com o GitHub:


