# GIT E GITHUB

####  Comandos GIT:

- **git init**: inicializa um repositório local git
- **git status**: verifica o estado dos seus arquivos
- **git add <nomeDoArquivo>**: envia seu arquivo especificado para o Stage
- **git add .**: envia todos os arquivos para o Stage
- **git commit -m “mensagem":** envia o que está no Stage para o HEAD
- **git remote add origin urlDoRepositorio:** adiciona e indica a URL do repositório remoto em que os arquivos serão mantidos
- **git push origin master:** envia os arquivos para o repositório remoto que você especificou através da URL do comando acima
- **git checkout -b <nomeDaBranch>:** cria uma nova branch
- **git checkout <nomeDaBranch>:** alterna para a branch especificada
- **git config --list**



#### Passo a passo para criar um repositório



- Primeiro crie seu repositório seu local. Sua pasta onde ficará seu projeto.
- Entre na pasta e clique com o botão direito do mouse. Selecione o Git Bash
- Para iniciar o repositório utilize o comando **“git init”** 
- Você pode verificar o status do repositório com o comando **“git status”**. É uma boa prática sempre conferir o status antes de iniciar com o fluxo das alterações e durante ele também
- Se você ainda não tiver nenhum arquivo nessa pasta, crie algum para continuar com o processo. Essa é a camada Working Directory.
- A próxima camada é o Index. Para mandar o seu arquivo para o index, basta utilizar o comando “**git add nomeDoArquivo**” ou se você quiser enviar ao Index todos os arquivos basta utilizar o parâmetro all. Assim: “**git add -all**”
- Para verificar se o git está acompanhando seu arquivo, dê o comando “**git status**”. Se estiver tudo certo, aparecerá esta mensagem, o que significa que seu arquivo criado está na camada Stage.
- Depois que seus arquivos novos ou modificados estiverem na camada de Stage, você pode commita-los, ou seja, envia-los à ultima camada do fluxo, HEAD. Para isso use o comando “**git commit -m “tituloDoCommit”**. O parâmetro “-m” é passado para que você possa escrever uma descrição junto ao commit.
- Agora a última etapa do fluxo é enviar o(s) arquivo(s) ao repositório remoto. Se você ainda não tem, crie um repositório remoto, pode ser no GitHub, GitLab ou qualquer outro de sua preferência.
- Depois de criado, copie a URL HTTP do seu repositório, ela será necessária.
- Volte ao Git Bash escreva o comando: “**git remote add origin urlDoRepositorio**”. Com esse comando você está especificando o repositório ao qual você deseja manter o seu projeto. “Origin” é apenas um apelido padrão, mas você pode utilizar qualquer nome.
- Depois de adicionado o repositório remoto, envie os arquivos utilizando o comando “**git push origin master**”
- Processo finalizado. Após o git push seus novos arquivos ou novas alterações já estão no repositório, você pode ir até lá verificar.

