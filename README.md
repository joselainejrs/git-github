<p align="center">
  <img  src="https://github.com/joselainejrs/git-github/blob/main/image.png" width="150px" alt="Imagem">
</p>

<h4 align="center">
O que é Git e GitHub e como usar?
</h4>

## O que é Git
### Sistema de controle de versão de código 

- Permitindo registrar mudanças realizadas no código e mante-las organizadas. Permitindo também ter o registro de todas as mudanças realizadas no projeto. 
- O uso mas comum pelos desenvolvedores é o gerenciamento de projetos de Software, mas também tem outros tipos de uso.
- Um ponto interessante do GIT é a facilidade que temos de compartilhar e termos um código colaborativo com outros desenvolvedores, pois ele é um sistema distribuído.

### Vamos de mais coisas 
### GIT funcinciona através de linha de comando

- Branch (ramificações): é uma processo que criamos para realizar alterações sem prejudicarmos o que está na nossa master.
- Master: É o projeto principal (código raiz)
- Merge: Processo que utilizamos para mescla o que foi feito na branch para master ou  antes para develop (que as empresa  utilizam muito )

## O que é GitHub
### É a plataforma online que fica todo o nosso código armazenado

- Nesse local nosso projetos ficam salvos na nuvem, podendo ser público ou privados  
- Como funciona: Para utilizarmos criamos um repositório e nesse repositório podemos utilizar o comando do git para subir o nossos projetos 
- Nele é possível visualizar o seu código e todo o seu projeto que foi construído. 
- Possibilitando também documentar nossos repositórios usando o arquivo README.med

## Mão na massa
### Preparando o ambiente

Pesquise por : git download
Link do download: `https://git-scm.com/downloads`

Abrir uma conta no Git Hub : 
Pesquise por GitHUb
Link: `https://github.com/`
Os próximos passos para criar uma conta na plataforma é bastante intuitivos

### Configuração da maquina
- Com a pasta aberta e tudo pronto para subir algo, o primeiro comando que rodamos no terminal é:

```
$ git config --global user.email "seu e-mail"
$ git config --global user.name "seu usuário"

```

- Inicializar um projeto
  
```
$ git init
$ git status  (para verificar o status do nosso git);
$ git add .  (processo para adicionar o arquivo);
$ git commit -m  "descrição";
$ git log  ver o histórico de commits
$ git push (para subir o código)
```


<h4 align="center">
Projeto desenvolvido por: Joselaine Romão Soares
</h4>

