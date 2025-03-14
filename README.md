# Instruções para Repositório Git

## Criação e Clone do Repositório

Crie um novo repositório no GitHub. Faça o clone desse repositório no seu computador, usando o terminal.

💡 **Dica**

```
Ao abrir o terminal, verifique em qual pasta você está. 
Nós iremos clonar o repositório na pasta do seu usuário no computador, então veja como fazer isso:
```
- **Windows**: abra o terminal do Git Bash e rode o comando `cd ~`

Usando o terminal, entre na pasta que o clone acabou de criar. Crie uma nova branch chamada `git-1` e acesse ela.

💡 **Dica**

    Para entrar na pasta do repositório clonado, use o comando `cd nome-da-pasta`.

Ao entrar, você automaticamente é colocado na branch `master/main`, e é possível criar uma branch nova usando o comando `git branch nome-da-branch`.

A sua branch foi criada, mas você ainda está na `master`! Para trocar de branch, use o comando `git checkout nome-da-branch`.

Nas próximas repetições, você vai criar branches com outros nomes, então tome cuidado!

## Criação de Pastas e Arquivos

Crie uma pasta chamada `aulagit` (sem espaços ou acentos). Vamos relembrar os comandos que vimos na aula de terminal!

💡 **Dica**

    Para criar uma pasta, você pode usar o comando `mkdir nome-da-pasta`.

Entre na pasta `aulagit` e crie uma pasta chamada `sobre-mim`.

💡 **Dica**

Sua estrutura de pastas ficará assim: `Nome-Repo > aulagit > sobre-mim`.

Entre na pasta `sobre-mim` e crie um arquivo chamado `minha-bio.txt`.

💡 **Dica**

    Para criar um arquivo em branco, você pode usar o comando `touch nome-do-arquivo`.

Agora você deve editar esse arquivo `minha-bio.txt`. Você deve escrever uma mini biografia sua de no máximo 50 palavras.

💡 **Dica**

    Para editar o arquivo, abra-o no seu editor de texto preferido (VSCode, Bloco de Notas, VIM, ou qualquer outro).

**Algumas ideias**: onde nasceu, onde mora, o que gosta de fazer nas horas livres, a antiga profissão antes de querer ser um desenvolvedor de software, o que te interessa em tecnologia... Use a criatividade, mas não perca muito tempo rebuscando o texto, pode ser algo simples.

Nas próximas repetições, você vai criar outros arquivos com nomes e conteúdos diferentes. Tome cuidado!

## Comandos Git

### Verificando o Status

Após salvar o arquivo, você realizou uma alteração no seu repositório! Veja como está o status do seu repositório.

💡 **Dica**

    Use o comando `git status`.

### Adicionando Arquivos à Staging Area

Faça um `add` do seu arquivo alterado, para que ele seja enviado para a Staging Area. Verifique o status do seu repositório novamente e observe as diferenças.

💡 **Dica**

    Use o comando `git add .` para adicionar todos os arquivos dentro de sua pasta atual à Staging Area.

Se quiser garantir que adicionou todos os arquivos dentro do repositório, independente de qual pasta você está, use o comando `git add --all`.

### Realizando o Commit

Faça um commit das suas alterações. Escreva uma mensagem breve explicando o que foi alterado.

💡 **Dica**

    Use o comando `git commit -m "mensagem-descrevendo-a-mudança-feita"`.

Não se esqueça que devem ser usadas aspas duplas `" "`.

### Enviando as Alterações para o Repositório Remoto

Hora de mandar as alterações para o seu repositório remoto! Faça o push das alterações – não se esqueça da branch em que você está!

💡 **Dica**

    Use o comando `git push origin nome-da-branch-que-você-está`.

### Voltando para a Branch Main/Master

Volte para a sua branch `main/master`!

💡 **Dica**

    No seu terminal, use o comando `git checkout main`.

## Repetindo os Passos com Novos Arquivos

Agora você vai repetir os passos acima mais 4 vezes, mas em cada uma delas, você deve:

1 - Criar uma branch com um nome diferente.

2 - Adicionar arquivos diferentes à pasta.

### Detalhes das Repetições:

- **Branch:** `git-2`  
  **Arquivo:** `musicas.txt`  
  O arquivo `musicas.txt` deve conter de 1 a 10 nomes das suas músicas favoritas.

- **Branch:** `git-3`  
  **Arquivo:** `filmes.txt`  
  O arquivo `filmes.txt` deve conter de 1 a 10 nomes dos seus filmes favoritos.

- **Branch:** `git-4`  
  **Arquivo:** `comidas.txt`  
  O arquivo `comidas.txt` deve conter de 1 a 10 nomes das suas comidas favoritas.

- **Branch:** `git-5`  
  **Arquivo:** `redes-sociais.txt`


Este arquivo deve conter algumas das redes sociais nas quais você tem conta! Pode colocar apenas o nome da rede social.

Ao final do exercício você deve ter criado 5 branches!


Este arquivo deve conter algumas das redes sociais nas quais você tem conta! Pode colocar apenas o nome da rede social.

Ao final do exercício você deve ter criado 5 branches!
