# GIT e Versionamento 

Versionamento e o registro de modificações dos códigos, sendo eles criados a partir de da raiz (main) do arquivo ou não, podendo ser unida as partes posteriormente. 

## Instalação 

Git pode ser instalado a partir do site https://www.git-scm.com/downloads e para verificar a instalação e versão instalada, usamos o comando.

```

 git --version

```

## Como usar o git

O git pode ser usado pelas seguintes aplicações:

* Git bash - instalado com o git
* CMD do Windows
* GitHub desktop - programa de extensão do site da github
* Site da GitHub 
* Terminal do VSCode


## Primeira configurando o Git

Usamos os comandos para definir globalmente o usuario e email com 

```

git config --global user.name "(nome do usuario)"  - para inserir o usuario do git.

git config --global user.email (email do usuario) - para inserir o email do usuario no git

```

## Repositórios

* Criando repositório Local

```

git init - inicia um repositório na pasta seleconada

git add README.md - inseri o arquivo de marcação markdown

```

* Clonando Repositório por https

```

git clone (caminho do repositório a ser clonado)

```
* Remoto 

## Estados do Git

* IMAGEM
  
O Git pode se encontrar em 4 seguintes estados que podem ser checados com o comando.

```

git status

```

1. Unmodefied - Estados aonde o codigo enconrase salvo e estatico.
   
2. Modified - Estado onde o codigo encotrase alterado do seu original.

3. Staged - Estado preparatorio antes do commit.

4. Untracked - ???

### Modificando o status do git:

Usamos o comando seginte para preparar o codigo pro estado staged apos o codigo ter sido alterado de unmodified para modified.

```

git diff - para verificar o a direrença entre o codigo unmodified do codigo modified
git add - para adcionar as modicações ao stado de staged


```

** Tambem podemos ver a diferença entre o codigo modified e o codigo staged com o comando antes do commit

```
git diff --staged
```

## Commit

E o registro final das alteraçoes da versão atual com a versão anterior.

```
git commit -m "(nome dado ao registro da alteração)"
```
### Registro de commits

Para vermos os  registros dos commits podemos usar o comando a seguir:

```
git log
```
### Restaurando commit/stados do codigo

```
git restore - permote voltar a ultimo estado do codigo
```







