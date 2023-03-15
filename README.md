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
 - Na parte de configurar as conversões de final de linha, a primeira opção **("Checkout Windows-style, commit Unix-style line endings")** é para os usuários de **Windows**, e a segunda opção **("Checkout as-is, commit Unix-style line endings")** são para usuários de **Linux** 🐧;
 - **IMPORTANTE:** Na hora de escolher o *credential helper*, é necessário selecionar a opção **"Git Credential Manager Core"** para se evitar problemas futuros na hora de realizar operações no Git, pois a opção **"Git Credential Manager"** se trata de uma opção defasada.
 - Após essas ressalvas, pode-se prosseguir com a instalação normalmente.
 - *Et Voilà!*, o Git está instalado!

2. Criando um repositório usando Git:
 
 - Vá no diretório C:/ do seu computador e crie uma pasta chamada `workspace`;
 - Dentro dessa pasta, clique com o botão direito do mouse e selecione a opção **"Git Bash Here"**;
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

 - Va no site do [GitHub](https://github.com/) e clique no botão **"Sign Up"** para entrar na sua conta ou criar uma nova;
 - **OBS:** é interessante que você tenha o mesmo nome e email configurados no Git e no GitHub, pois isso ajuda na hora de relacionar os commits que você fez, para verificar como estão configurados esses dados no seu Git, você pode digitar `git config --list` onde ele vai devolver uma lista com diversos dados, entre eles o email e nome de usuário que você está usando;
 - Caso seja necessário alterar, digite `git config --global --unset user.email` para o email e `git config --global --unset user.name` para o *user name*;
 - Após isso, é só configurar de novo esses dados usando `git config --global user.email "seu email aqui"` e `git config --global user.name seu_nome`;
 - Agora para verificar seus repositórios, clique no canto superior direito e escolha a opção "Seus repositórios" (ou *"Your Repositories"*);
 - Para criar um novo repositório, clique no botão verde escrito *"New"*:
 - Adicione um nome, uma descrição, decida se ele será público ou privado e se ele terá um arquivo de **README** ou não e clique em *"Create Repository"*;
 - Agora copie o link do repositório remoto (ele vai ser parecido com algo como: `https://github/SeuNomeDeUsuario/NomeDaPasta.git`);
 - Agora iremos apontar o nosso repositório local da nossa máquina para o repositório remoto do Git, para isso devemos digitar: `git remote add origin endereco_que_copiou_do_github.git` e depois `git push origin master`.

Fim do tutorial 😃

