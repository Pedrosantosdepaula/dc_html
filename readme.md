# comandos  basicos git

![git](/assets/gitlogo.png)
## 1. clonando projeto

### 1.1 criar o repositorio, no nosso caso, no github

### 1.2 ir para a pasta na maquina e abrir o terminal e executar o comando abaixo.

```shell
git clone [url_github]
```
acessar a pasta do projeto clonado

```shell
cd [nome_repositorio]
```

## 2. subindo o codigo do projeto
<ol>
   
   ### 2.1. status
   ```shell
   git status
   ```
   ### 2.2 adicionar todos os arquivos 
   ```shell
   git add.
   ```
   ### 2.3 preparar todos os arquivos 
   ```shell
   git commit -m "[mensagem]"
   ```

   ### 2.4 enviar as alterações
   ```shell
   git push
   ```
   ## 3. configurando o usuario global no SO
   **Fonte:** [Configuração Inicial do Git](https://git-scm.com/book/pt-br/v2/Come%C3%A7ando-Configura%C3%A7%C3%A3o-Inicial-do-Git)

   ```shell
   git config --global user.name "[nome_usuario_github]"
   git config --global user.email [email_usuario_github]
   ```