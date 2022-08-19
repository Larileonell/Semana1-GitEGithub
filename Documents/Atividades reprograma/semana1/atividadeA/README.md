# COMANDOS BÁSICOS GIT 
*git* config user.name "Nome da Reprogramer": configura o seu nome

*git* config user.email "emailDaReprogramer@gmail.com": configura o seu email

*git* config --list: mostra todas as propriedades de configuração do Git 

*ls*: listar (ele traz uma lista de tudo o que está naquela pasta - 
documentos, outras pastas, etc)

*mkdir* nome-da-pasta: cria uma pasta

*touch* nome-do-arquivo: cria um arquivo

*cd*: usado para se locomover entre as pastas

*cd* ~ : volta para a pasta raiz

*cd* .. : volta uma pasta

*pwd*: traz o caminho onde você está (em que pasta e onde essa pasta fica)

*rm* arquivo: remove, deleta um arquivo.

*rm* -f ou rm --recursive pasta: deleta uma pasta

*whoami*: "quem sou eu?" identifica o usuário que está mexendo no sistema

*git init*: inicializa o git no repositório local

*git commit -m*: é usado para criar um instantâneo das alterações preparadas em um cronograma de um histórico de projetos do Git.

*git add nome-do-arquivo*: adiciona um arquivo modificado ao stagging (área temporária) 

*git add .*:adiciona todos os arquivos modificados ao stagging (área temporária) 

*git status*: mostra os status dos arquivos modificados

*git commit -m "mensagem"*: cria um commit

*git pull*: puxa as atualizações mais recente (remoto -> local)

*git push*: envia as atualizações mais recentes (local -> remoto)

*git remote add origin nome-da-branch*: faz um link entre seu repositório local com o remoto 

*git checkout -- nome-arquivo*: descarta as alterações locais do arquivo informado

*git checkout -b nome-da-branch*: cria uma branch a partir da atual

*git checkout nome-da-branch*: troca de branch

*git merge nome-da-branch*: mescla a branch passada no parâmetro com a atual

*git remote -v*: mostra as URLs para onde o git está apontando

*git log*: mostra o histórico de commits, com data, hora, mensagem e autora (caso fique presa nessa lista, aperte "q" para sair)

*git branch*: lista todas as branchs locais

*git diff*: mostra no terminal a diferença entre os arquivos editados localmente
## Conceitos básicos

Repositório: espaço digital aonde o seu projeto vai ser salvo. No seu computador ele é a pasta aonde o seu projeto está salvo.

Commit: controle de versão (histórico) daquele arquivo e cria uma etiqueta para facilitar o entendimento do que foi salvo naquele momento.

Pull: serve para se comunicar entre a sua máquina e o repositório remoto. Esse comando faz uma cópia do repositório remoto e baixa ele para a sua máquina.

Push: serve para se comunicar entre a sua máquina e o repositório remoto. Esse comando faz uma cópia do repositório local e envia ele para o repositório remoto.

Clone: faz exatamente o que ele sugere: uma cópia exata do arquivo, que você vai baixar do repositório remoto para a sua máquina.

Branch: permite que cada usuário tenha o seu "galho" dentro de um projeto de maneira independente. Ela é uma parte muito útil no desenvolvimento em um projeto coletivo.

Merge: unifica diferentes branches

Fork: cria uma cópia de um projeto para o seu GitHub

Pull Request(PR): solicitação de dar merge da sua branch em um projeto de outra pessoa
##      Commits semânticos 
**Commit semântico ou conventional commit**, é uma das formas que se pode fazer padronização de commits dentro de um projeto de desenvolvimento de software.
Utilizando regras simples e claras, que apesar de introduzirem uma pequena carga adicional de trabalho, irá contribuir para que seja reduzido o tempo gasto em compreender como e por que algo foi feito em um alteração ou correção posterior.