
# Resumos | Aula 07

Para puxar as alterações do seu repositório remoto para o repositório local, você pode utilizar o comando 'git pull':

- Para isso, primeiro certifique-se que está na branch correta que irá receber as atulizações:

```
git checkout sua_branch
```

- O comando responsável por puxar as alterações é o 'git pull', ele irá puxar as informações do seu repositório remoto, e atualizar o seu reporitório local (geralmente 'main' ou 'master'), segue o comando:

```
git pull origin sua_branch
```

O comando 'git pull' é uma combinação de:

- 'git fetch'(comando utilizado para baixar as informações do repositório remoto), e
- 'git merge' (comando utilizado para mesclar as alterações na sua branch local).

Sendo assim, caso o seu repositório local tiver alguma alteração que ainda não foi confirmada, ao fazer o git pull, resultará em um conflito de merge, pois o git tentará mesclar as branchs automáticamente. Se ocorrer o conflito de merge, e precisar de alguma ajuda para resolver, consulte o resumo da [aula 14 - Conflito de Merge](/resumos/)

<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




