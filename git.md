# resumo dos comando mais usados do git

### init

*init* é usado prar inicializa um novo arquivos do novo repositorio,digitar:

Exemplo:

```bash
$git init
```

### status

*status* mostrar o estado atual do repositorio

Exemplo:
```bash
$git status
```
uam forma resumida de listar o status é usando a opção '-s'

```bash
$git status -s
```


 ### camando de cadastro 

 o comando de cadastro é usado para configurar informações essenciais do usuário, como nome e e-mail.

 Exemplo:
```bash
$git config --global user.name "seu nome"
```
serve para cadastar seu nome de usuario.


```bash
$git config --global user.email "seu email"
```
sever para cadastar seu email.


### ver os diretórios

o camando *ls* server para os diretorios.

```bash
ls
```

### acessar pastas

o comando *cd* + nome da pasta serve para acessar a pasta desejada.
```bash
cd + nome da pasta
```

### criar uma pasta

o comando *mkdir* + nome da pasta server para poder criar uma pasta.

```bash
mkdir + nome da pasta
```

### criar um aquivo 

o camando *touch* + nome do aquivo + tipo do arquivo, serve para criar um arquivo dentro de uma pasta.

```bash
touch + nome do aquivo + tipo do arquivo
```

### fazer um commit

o camando commit server para adicionar um comentario sobre as alterações no projeto

```bash
git commit -m "sua mensagem"
```

### historico de commit

o camando *git log* serve para mostar os historicos de commit ja feito no projeto.

```bash
git log
```

### clonar um repositorio

o comando git clone + URL sarve para clonar um repositorio do github.
