<h1 align="center">
   Git Alias
</h1>

# Requisitos
-   [VS Code](https://code.visualstudio.com/)
-   [Git](https://git-scm.com/)

# O que são?
São atalhos. Atalhos pro quê? São atalhos para comandos do git e até comandos shell se você quiser. 
E é bem fácil cadastrar um alias:

## Como cadastrar?
Primeiro em seu terminal execute o comando:
```bash
$ git config --global --edit
```
Você pode escolher entre três opções: --global / --local / --system

Para configurar usando o [VS Code](https://code.visualstudio.com/), execute o comando:
```bash
$ git config --global core.editor code
# Após executar esse comando, execute novamente o comando acima para abrir com Vscode
```
