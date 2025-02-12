# Trabalhando sozinho no git/github
1.  Instalar o git
2.  o git é uma ferramenta [programa] no seu sistema operacional.
3.  por sua vez o github é uma rede [social/plataforma] aonde você armazena seus projetos.
4.  Repositório local é quando o [projeto/commits/branchs] ainda está no seu computador.
5.  Repositório remoto é quando o projeto está na [nuvem], ex: github, fonte, gitlab...

## Criando um repositório local pelo git
1.  Abrir o projeto no [vscode]
2.  Abra o terminal no vscode, CTRL+J ou CTRL+'
3.  `git init` -> Inicializa o repositório local
4.  `git status` -> Exibe se os arquivos/pastas estão adicionados ao repositório local.
5.  `git add nome_do_arquivo` -> Adiciona os arquivos/pastas ao repositório local
6.  `git add.` -> Adiciona todos os arquivos/pastas ao repositório local
7.  `git commit -m "Mensagem da atualização"` -> Cria um commit para que seja realizado uma nova versão do projeto
8.  `git log` ->  Lista os commits que foram realizados.
9.  `git log --oneline --graph --decorate` -> Forma compacta de exibir os commits.
11. `git branch -M main` -> Força a criação de uma branch chamada main.
12. `git checkout nome_da_branch` -> Muda a branch.
13. `git branch` -> Exibe as branchs cridas.
14. `git remote add origin https://exemplo.com` -> Realiza a sicronização do repositório local com o remoto.
15. `git push -u origin main` -> Envia as informações do repositório local para o repositório remoto.
16.  `git clone https://exemplo.com` -> Clona um repositório.


## Comandos VScode
`SHIFT + HOME` -> Seleciona toda a linha.
