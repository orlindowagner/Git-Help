# Git-Help
Lembrete de comandos úteis do git


## Para diretório já presente no computador

### Localizar e verificar mudanças
- cd ./nome_do_diretorio
- git status

### Comandos para subir para o git (sincronização PC >> Github)
```
git add nome_do_item 
git commit -m "comentário para esta commit indicando a mundança"
git push origin master

```
### Comando para puxar do git (sincronização Github >> PC)
- git pull origin master

## Comandos básicos para usar o git

## Para iniciar do zero
- git clone "url_copiado_do_github"
ou
- Fazer o download e executar: git init (quando estiver dentro da pasta)

### Comandos de configuração de usuário
- git config --global user.name "user_name"
- git config --global user.email "user@email"






## Outros comamndos úteis
### Comandos para saídas

- git init  (inicia o git no diretorio)
- rm -rf .git (desliga o git do diretorio)
- git config --unset-all --global user.name   (dá saída do user_name atual)
- git config --unset-all --global user.email  (dá saída do user_email atual)

### Organização

Ctrl+L  (serve para limpar a tela do terminal)

