# Resumos | Aula 13

### 📁 Arquivando Modificações:

O comando git stash é utilizado para arquivar modificações que não desejamos usar imediatamente. Por exemplo, ao criar uma nova branch, podemos arquivar modificações para evitar que sejam transferidas para essa nova branch.

Para listar as modificações arquivadas até o momento, utilizamos:

```
git stash list
```

Para criar uma nova branch, utilizamos o comando .

```
git checkout -b teste-2
```


Para excluir a modificação arquivada mais antiga.
```
git stash pop
```

Se você quiser excluir uma modificação específica arquivada pelo git stash, o comando git stash pop excluirá o primeiro da lista. No entanto, se preferir prosseguir com a modificação mais recente, utilize o comando git stash apply. Este comando aplicará as modificações mais recentes arquivadas sem excluí-las do stash.


<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




