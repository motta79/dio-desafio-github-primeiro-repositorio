# Repositório do Desafio de Projeto Sobre Git/Github da DIO
Repositório criado para o Desafio de Projeto
## Links Úteis
[Sintaxe Básica Markdown](https://www.markdownguide.org/getting-started/)

[Sintaxe Editor Markdown online](https://dillinger.io/)     
## O que são Git e GitHub?
Git
Git ₍ₒᵤ em inglês britânico₎ é um sistema de controle de versões distribuído, usado principalmente no desenvolvimento de software, mas pode ser usado para registrar o histórico de edições de qualquer tipo de arquivo. (Wikipédia)

GitHub
GitHub é uma plataforma de hospedagem de código-fonte e arquivos com controle de versão usando o Git. Ele permite que programadores, utilitários ou qualquer usuário cadastrado na plataforma contribuam em projetos privados e/ou Open Source de qualquer lugar do mundo. (Wikipédia)

## Qual a diferença entre Git e GitHub?
Em suma, o Git é um software de controle de versão, já o GitHub é como se fosse uma rede social de pessoas desenvolvedoras, ou seja, uma plataforma na qual podem compartilhar projetos. (Driven)



## Principais comandos do Git
* Git init *
  
  Com sua pasta de trabalho devidamente iniciada, é hora de começar a preenchê-la.

Git clone

  Quando você clonar um repositório, o código é copiado para a o seu computador e continua linkado ao original, como foi explicado lá na descrição do que é um sistema distribuído.

Git branch

  Este comando criará uma branch local. Para upar a nova branch para o repositório remoto, você precisa usar o seguinte comando: git push -u <remote> <nome-da-branch>

Git checkout

  Esse é um dos comandos git mais utilizados. Para trabalhar em uma branch, primeiro você precisa mudar para ela. Apesar de parecer algo óbvio, não ir para a branch que você acabou de criar e na qual quer trabalhar é um erro bastante comum no começo.
  
Git status

  O comando Git status serve para fornecer algumas informações importantes sobre a branch em que você estiver no momento, incluindo se ela está atualizada em relação à master e quais arquivos foram alterados.  

Git diff
  
  Apesar de o git status fornecer muitas informações relevantes, às vezes é preciso ir além.  

  Caso você queira, por exemplo, saber exatamente o que você alterou (e não apenas quais arquivos foram alterados), o melhor a se fazer é utilizar o comando: git diff. 

Git add

  Quando criamos, modificamos ou excluímos um arquivo, essas alterações ocorrerão em nosso ambiente local e não serão incluídas no próximo commit (a menos que alteremos as configurações).

  Para incluir as alterações de um arquivo em nosso próximo commit, será preciso usar o comando git add.

  Para adicionar apenas um arquivo:

git add <arquivo>
  
  Para adicionar, de uma vez, todos os arquivos modificados:

Git commit

  Relembrando, esse comando visa definir um ponto de verificação no processo de desenvolvimento, para o qual você pode voltar mais tarde, se necessário.

git commit -m "mensagem explicando a mudança no código"
  
Git push
  
  Após confirmar as alterações, a próxima coisa que você deseja fazer é enviar as alterações para o servidor remoto usando o comando git push:

git push <remote> <nome-do-branch>
No entanto, se seu branch for criado recentemente, você também precisará fazer upload do branch com o seguinte comando:

git push -u origin <nome-do-branch>

Git pull

Git revert

Git merge

Git stash
  
  ## Referências:
WIKIPÉDIA. Disponível em: https://pt.wikipedia.org/wiki/Git. Acesso em: 14 mar. 2023.

WIKIPÉDIA. Disponível em: https://pt.wikipedia.org/wiki/GitHub. Acesso em: 14 mar. 2023.

DRIVEN. Disponível em: https://www.driven.com.br/blog/qual-a-diferenca-entre-git-e-github/. Acesso em 14 mar. 2023.
