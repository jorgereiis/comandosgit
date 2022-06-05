<h1 align="center">Comandos para uso diário do Git</h1>

<ol>
    <li><h3>git remote add origin git@github.com:userGitHub/nomeDoRepositório.git</h3></li> 
    Cria um "apelido" pro repositório no GitHub. Nesse caso o apelido é Origin, comumente é usado esse nome para o repositório padrão;
    <li><h3>git init</h3></li> 
    inicia o git na pasta selecionada;
    <li><h3>git status</h3></li> 
    Mostra o status das alterações;
    <li><h3>git add 'nomeDoArquivo'</h3></li>     
    Adiciona o arquivo ao monitoramento de alterações do git;
    <li><h3>git add -A // git add * // git add .</h3></li>     
    Adiciona todos os arquivos que não estão sendo monitorados ao monitoramento do git;
    <li><h3>git commit -m 'Resumo das alterações'</h3></li>     
    commita as alterações para o branch que está sendo trabalhado (ou o branch master, preciso ver ainda);
    <li><h3>git commit -a -m 'Resumo das alterações'</h3></li>     
    commita as alterações para o branch que está sendo trabalhado, já adicionando todos os arquivos (tirando a necessidade do git add);
    <li><h3>git branch</h3></li> 
    Vê os branchs existentes e sinaliza o que está sendo utilizado no momento com um *;
    <li><h3>git branch 'nome'</32></li> 
    Cria uma nova branch;
    <li><h3>git checkout 'nome'</h3></li> 
    Altera o branch que está sendo usado;
    <li><h3>git diff</h3></li> 
    Mostra o que foi alterado antes de dar commit em um arquivo;
    <li><h3>git diff --name-only</h3></li> 
    Mostra somente os nomes dos arquivos que foram modificados;
    <li><h3>git reset --soft 'códigoDoCommit'</h3></li> 
    Reseta o arquivo para um commit anterior sem perder o que foi alterado;
    <li><h3>git reset --hard 'códigoDoCommit'</h3></li> 
    Reseta o arquivo para um commit anterior apagando todas as alterações feitas;
    <li><h3>git reset --mixed 'códigoDoCommit'</h3></li>
    Reseta o arquivo para um commit anterior sem perder o que foi alterado, porém é necessário adicionar os arquivos novamente;
    <li><h3>git revert --no-edit 'códigoDoCommit'</h3></li> 
    Da um commit revertendo o que foi feito no commit especificado. Mudando os arquivos, porém possibilitando "commitar" novamente o mesmo posteriormente;
    <li><h3>git push 'apelidoRepositorioGitHub' 'nomeBranch'</h3></li> 
    Envia o branch selecionado ao repositório GitHub;
    <li><h3>git push 'apelidoRepositorioGitHub':'nomeBranch'</h3></li> 
    Deleta o branch do repositório GitHub
    <li><h3>git branch -D nomeBranch</h3></li> 
    Deleta o branch local;
    <li><h3>git pull 'apelidoRepositorioGitHub' 'nomeBranch'</h3></li> 
    Recebe o repositório GitHub no branch selecionado;
    <li><h3>git clone 'linkRepositorio'</h3></li> 
    Clona um repositório do link especificado na pasta selecionada no terminal;
    <li><h3>git remote -v</li></h3>
    Mostra o apelido dos repositório remotos;
</ol>
