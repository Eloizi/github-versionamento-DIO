
# Resumos | Aula 08

Para enviar as alterações do seu repositório local para o repositório remoto, você pode utilizar o comando 'git push':

- Para isso, primeiro certifique-se que as alterações realizadas já foram "commitadas":

    ```
    git status
    ```

### ▶ Changes to be committed

Se aparecer algum arquivo sob o título “Changes to be committed”, os arquivos já foram adicionados e estão esperando para serem commitados, exemplo:

![arquivos esperando para serem commitados](https://guilherme.readthedocs.io/en/latest/_images/git05.png)

### ▶ Untracked files

Se os arquivos estiverem sob o subtítulo “Untracked files” ➡ Não foi rastreado". 
Basicamente significa que o Git está enxergando um arquivo que não tinha no snapshot (commit) anterior. Para incluir o arquivo no próximo commit é necessário dar o comando:
-  "git add exemplo_arquivo.md" ➡ especificando qual arquivo quer preparar para o próximo commit, ou 
- "git add ." ➡ O ponto, serve para adicionar todos os arquivos que ainda não foram rastreados, sem a necessidade de especificar cada um deles.

Exemplo:
![arquivos esperando para serem commitados + arquivos que ainda não foram rastreados](https://phoenixnap.com/kb/wp-content/uploads/2022/09/check-untracked-files.png)


### ▶ Changes not staged for commit
Se aparecer algum arquivo sob o título “Changes not staged for commit”.
Indica que um arquivo rastreado foi modificado no repositório local mas ainda não foi mandado para o stage (estado de preparação) para fazer isso é necessário adiciona-los, com o comando "git add"

 ![Arquivos que ainda não foram adicionados](https://linuxhint.com/wp-content/uploads/2023/05/What-Does-Changes-not-staged-for-commit-Mean-6.png)


## Git Push
Após se certificar que os arquivos estão corretamente adicionados, só dar sequência no comando:

```
git push origin sua_branch
```

<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




