
# Resumos | Aula 02

### 🚩 O que é Snapshot no Git?
> No contexto do Git, um "snapshot" refere-se a uma versão específica do seu projeto em um determinado ponto no tempo. Cada commit no Git cria um snapshot do estado do repositório naquele momento. Esses snapshots incluem todas as alterações realizadas nos arquivos do projeto desde o último commit.
<br>

## 🔄 Entendendo o ciclo de vida dos arquivos:

 Um arquivo no seu repósitório pode estar em dois status:
 ```diff
- Untracked
→ São arquivos que não fazem parte do seu último snapshot e não foram adicionados no Git;

+ Tracked 
→ São arquivos que estavam no seu último snapshot, ou seja, são reconhecidos pelo Git e podem ter o status de unmodified, modified ou staged.
```
<br>

De forma resumida:
 |Status| Descrição|
 |------|----------|
 |Untracked| Um arquivo é criado no repositório ficando com o status untracked;|
 Tracked| depois de ser adicionado ao Git ele passa o status tracked staged (pronto para o commit);|
 |Modified|  após o arquivo ser editado seu status muda para tracked modified. |
 |Unmodified| Após o commit o arquivo muda o status para tracked unmodified.|


<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>






