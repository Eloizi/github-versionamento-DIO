O que é uma Branch, e para quê serve?

# Resumos | Aula 09

### 🌿 O que é uma Branch e para que serve?

Uma branch, ou "ramo" em tradução, é uma ramificação do seu projeto, funcionando como uma duplicata. É comumente utilizado para testar modificações sem afetar diretamente o arquivo principal. Ao criar uma nova branch a partir de outra existente, ela começa apontando para o mesmo commit da branch original no momento da criação, funcionando como um ponteiro móvel no histórico do repositório.

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

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




