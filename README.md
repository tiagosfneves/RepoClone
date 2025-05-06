# RepoClone
Estudos sobre Git para projetos já iniciados no GitHub. Para executar estes comandos, você precisará baixar o terminal Git na sua máquina. Se ainda não fez isso, você pode visitar o site do Git, <a href="https://git-scm.com/downloads" target="_blank">aqui.</a>

# Objetivos
Reconhecer o passo a passo básico para clonar (copiar) um repositório remoto e poder editar, "commitar" e publicar as alterações no GitHub usando comandos do Git.

## PASSO 1 - CLONAR:
- <b>Clonando um repositório existente do GitHub para seu computador:</b>
    - git clone URL_DO_REPOSITORIO
    - cd nome/do/repositorio
    - <b>Resultado:</b> Você terá uma cópia do repositório remoto na sua máquina com todas as pastas e arquivos.

## PASSO 2 - EDITAR e "COMMITAR" o CLONE:
- <b>Publicando alterações locais para o repositório remoto, após clonar e fazer alterações no seu computador:</b>
    - git add NOME_DOS_ARQUIVOS
    - git commit -m "Descreva o que foi feito"
    - git push origin NOME_DA_SUA_BRANCH
    - <b>Resultado:</b> Todas as modificações serão publicadas no GitHub.

## PASSO 3 - IGNORAR ARQUIVOS
- <b>Criando, adicionando arquivos para ignorar e publicando .gitignore:</b>
    - dentro do repositório local, crie o arquivo  de nome: .gitignore
    - para ignorar arquivos com dados sigilosos, senhas etc, faça:
         - abra o arquivo .gitignore
         - liste os arquivos explicitamente, exemplo: teste.html, img.png
         - ou ignore todos com as mesma extensão usando asterisco, exemplo: *.html
    - para add comentários use o símbolo cerquilha " # ", por exemplo: #BLACKLIST
