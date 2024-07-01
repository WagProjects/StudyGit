# DIO | Resumos Git e GitHub

Repositório para armazenar resumos sobre Git e GitHub do curso Versionamento de Código com Git e GitHub


## 📚 Documentação
Start a new Git repository for an existing code base

    $ cd /path/to/my/codebase
    $ git init
    $ git add .
    $ git commit -m "projeto inicial"
    $ git remote add origin git@github.com:SEU_USUARIO/SEU_REPOSITORIO
    $ git push origin main

Para configurar a identidade do autor do commit, digite no terminal o comando:

    $ git -config --global user.email "seuemailaqui@example.com"
    $ git config --global user.name "seu nome aqui"

Para criar a branch Main, digite no terminal o comando: ``git branch -M main``
O comando git branch -m é usado para criar uma nova ramificação no repositório Git atual. Neste caso, criamos a branch padrão main, que representa a versão principal do código.

Para realizar a conexão do seu repositório local com o remoto via SSH, digite no terminal: ``git remote add origin https://github.com/seunomedeusuario/seu-repositorio.git``
Caso seja necessário, realize a configuração do protocolo SSH através da geração de chave.
