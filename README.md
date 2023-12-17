
# Resumo Git e GitHub

O presente repositório é dedicado a apresentar um breve resumo a respeito de Git e GitHub no versionamento de código, com base no curso da DIO sobre Versionamento de Código com Git e GitHub, ministrado por [Elidiana Andrade](https://github.com/elidianaandrade).

## ☝️ Git

O Git se trata de um sistema de controle de versões distribuído, ele é gratuito e open-source.

## 🐈‍⬛ GitHub

O GitHub por sua vez, trata-se de uma plataforma de hospedagem de código para controle de versões com Git, especialmente para a colaboração de equipes.

## Instruções

Para seguir estas instruções é necessário que você tenha instalado em seu computador o Git, seja no [Windows](https://git-scm.com/download/win), [Linux](https://git-scm.com/download/linux) ou [MacOS](https://git-scm.com/download/mac) e também possua uma conta no GitHub.

## Comandos Úteis
- Inicializando um repositório local 

De maneira simples, após criar uma pasta com arquivos em seu computador, você pode criar um repositório local. Basta abrir o Git Bash na pasta em questão e dar o seguinte comando:

```
git init
```

- Conectando o repositório local ao remoto

O repositório remoto é aquele presente aqui no GitHub. Sendo assim, para realizar a conexão com seu repositório local, basta, primeiramente, criar um novo repositório no GitHub e copiar o link deste repositório. Em seu terminal dê o seguinte comando, substituindo URL pelo link copiado:

```
git remote add origin URL
```

- Clonado um conteúdo do repositório remoto

Suponhamos que você criou um arquivo, por exemplo um READ.me, em seu repositório remoto e agora deseja trazer este arquivo para seu repositório local. Para isso basta utilizar o seguinte comando, substituindo URL pelo link de seu repositório remoto, semelhante ao procedimento realizado no ponto anterior:

```
git clone URL
```

- Salvando alterações no repositório local

Caso você altere o conteúdo de qualquer arquivo em seu repositório local, para salvar essa alteração via Git, é necessário utilizar uma sequência de dois comandos:

```
git add .
git commit -m "mensagem"
```
Dessa maneira, ao utilizar o primeiro comando, você adiciona as alterações realizadas em todos os seus arquivos em uma área temporária. No caso do segundo comando, você efetiva as alterações realizadas e deve substituir "mensagem" por uma mensagem que represente a alteração realizada.

Se você deseja salvar a alteração de um arquivo específico basta inserir o nome do arquivo na sequencia do comando. No exemplo de uma alteração no arquivo READ.me, teríamos:

```
git add READ.me
```

Não se esqueça de na sequência, dar o comando ```git commit``` para salvar as alterações, já que o ```git add``` salva as alterações temporariamente, numa área chamada **stage**.

- Dica

Uma dica para melhor compreensão das alterações feitas a cada comando é utilizar o comando ```git status``` ou ```git log ```.

O comando ```git status``` exibe as condições do diretório de trabalho e da área de staging. Ele permite que você veja quais alterações foram despreparadas, quais não foram e quais arquivos não estão sendo monitorados pelo Git.

O comando ```git log```, por sua vez, exibe instantâneos que receberam commit. Ele permite que você liste e filtre o histórico do projeto e pesquise alterações específicas.

- Subindo as alterações feitas no repositório local para o remoto

Após fazer um commit, você salvou as alterações feitas em seu repositório local, mas como salvar isso no repositório remoto? Ou seja, no GitHub?
Basta dar o comando abaixo:

```
git push
```

Pronto, se agora você abrir novamente o repositório no GitHub, ele estará modificado com as alterações que você fez localmente.

- Pegar as alterações feitas no repositório remoto para o local

E caso contrário? Se você fizer as alterações no próprio repositório remoto e agora desejar salvar essas alterações em seu repositório local, basta utilizar o comando a seguir:

```
git pull
```




## Contato

Entre em contato comigo pelo meu 
[LinkedIn](https://www.linkedin.com/in/patr%C3%ADcia-cresc%C3%AAncio-martins-39390925a/).
