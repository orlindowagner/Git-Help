# Git-Help
Lembrete de comandos úteis do git

## Comandos básicos para usar o git

## Para iniciar do zero
- git clone "url_copiado_do_github"
ou
- Fazer o download e executar: git init (quando estiver dentro da pasta)

### Comandos de configuração de usuário
- git config --global user.name "user_name"
- git config --global user.email "user@email"

## Para diretório já presente no computador
- cd ./nome_do_diretorio

- git add .         (para adicionar todo o conteudo do diretorio)

- git add FILE.xxx  (para adicionar somente o FILE.xxx)
- git commit -m "Comentario_colocado_indicando_a_mudança"
- git push origin master  (para empurrar o conteudo da pasta para o github)

### Comandos de sincronização
- git status  (muito útil para verificar se hove mudança em algum arquivo no computador)
- git pull origin master

## Outros comamndos úteis
### Comandos para saídas

- git init  (inicia o git no diretorio)
- rm -rf .git (desliga o git do diretorio)
- git config --unset-all --global user.name   (dá saída do user_name atual)
- git config --unset-all --global user.email  (dá saída do user_email atual)

### Organização

Ctrl+L  (serve para limpar a tela do terminal)

