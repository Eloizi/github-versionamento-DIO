O que é uma Branch, e para quê serve?

# Resumos | Aula 10

### O que é Conflito de Merge?

Esse problema por acontecer quando existes alterações concorrentes, isso é,  quando duas pessoas alteram a mesma linha de código, e quando um dos dois tenta enviar essas alterações, acaba gerando um conflito com que o outro havia enviado, pois o git não vai entender qual das alterações precisa ser mantida, então ele retorna esse erro, para que você decida qual alteração você deseja manter. Exemplo, tenho um arquivo que foi editado através da plataforma do gitHub, e outra que foi alterado através das linhas de comando. Quando tento enviar para o meu repositório remoto, ele dará um erro, tipo o exemplo:

exemplo:
![arquivos esperando para serem commitados](https://git-scm.com/book/en/v2/images/two-branches.png)


### 💻 Comandos para trabalhar com as Branches

- Criar uma nova Branch:
    ```
    git branch nome-da-nova-branch
    ```

- Mudar para uma Branch Existente:
    ```
    git checkout nome-da-branch
    ```

- Criar uma nova Branch e Mudar para ela:
    ```
    git checkout -b nome-da-nova-branch
    ```
- Informar qual Branch você está no momento:
    ```
    git branch -v
    ```

- Listar toas as Branches Locais:
    ```
    git branch
    ```

- Listar todas as Branches (Locais e Remotas):
    ```
    git branch -a
    ```

- Excluir uma Branch Local:
    ```
    git branch -d nome-da-branch
    ```
    - Para forçar a exclusão use -D
        ```
        git branch -D nome-da-branch
        ```

## Mesclando Branches:
O comando git merge nomeBranch no Git é utilizado para mesclar as alterações de uma branch específica (nomeBranch) em sua branch atual.

### 1º Posicionamento na Branch Atual:
Antes de tudo, você precisa estar na branch para a qual deseja mesclar as alterações. Você pode usar o comando git checkout ou git switch para mudar para a branch de destino.

### 2º Execução do Comando de Mesclagem:

Você executa o comando git merge nomeBranch, indicando a branch da qual deseja trazer as alterações (nomeBranch) para a branch atual:

```
git merge nomeBranch
```

Após o comando o git analisará as alterações feitas em ambas as branches (a atual e a branch a ser mesclada) e tenta fundi-las automaticamente.

### 3º Possíveis Conflitos:

Se houver conflitos entre as alterações (ou seja, modificações no mesmo local do código em ambas as branches), o Git pausará o processo de mesclagem e indicará que há conflitos a serem resolvidos. Dúvidas acesse o resumo da [aula 10](/resumos/).

### 4º Confirmação da Mesclagem:

Após resolver os conflitos (se houver), você conclui o processo de mesclagem e confirma as alterações. Isso cria um novo commit que incorpora as mudanças de ambas as branches.

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




