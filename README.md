# Git-Help
Lembrete de comandos úteis do git

## Comandos básicos para usar o git

## Para iniciar do zero
- git clone "url_copiado_do_github"

## Para diretorio já presente no computador
- cd ./nome_do_diretorio
- git config --global user.name "user_name"
- git config --global user.email "user@email"
- git add .         (para adicionar todo o conteudo do diretorio)

- git add FILE.xxx  (para adicionar somente o FILE.xxx)
- git commit -m "Comentario_colocado_indicando_a_mudança"
- git push origin master  (para empurrar o conteudo da pasta para o github)

### Comandos de sincronização
- git status  (muito útil para verificar se hove mudança em algum arquivo no computador)
- git pull origin master


## Comandos para saídas

- git init  (inicia o git no diretorio)
- rm -rf .git (desliga o git do diretorio)
- git config --unset-all --global user.name   (dá saída do user_name atual)
- git config --unset-all --global user.email  (dá saída do user_email atual)



