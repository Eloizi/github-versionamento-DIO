# Resumos | Aula 11

### Atualizando o Repositório Local Sem Mesclar com as Alterações do Repositório Remoto


Suponha que houve alterações no meu repositório remoto e desejo baixá-las para o repositório local sem mesclá-las imediatamente. Utilizo o comando "git fetch nomeRepoRemoto nomeRepoLocal", como exemplificado:

![baixando informações do repo remoto para o repo local](/img/baixar-repo-remoto-repo-local.jpg)


Utilizando o git diff, podemos comparar as duas branches para ver as alterações. Por exemplo, se eu quiser comparar a minha branch 'main' com a branch remota 'origin/main', eu utilizo o comando:

```
git diff main...origin/main
```

![exemplo da utilização do comando git diff](/img/git-diff.jpg)

### No exemplo acima eu utilizei o mesmo comando porém sem as reticências, qual a diferença?

Para a comparação existe duas formas, com o uso dos três pontos (...), e com o uso dos dois pontos (..), caso você não especifique qual dos dois quer usar, o Git assume implicitamente o uso dos dois pontos (..).

Escrevendo assim:

```
git diff main origin/main
```

O Git assume como:

```
git diff main..origin/main
```

A escolha entre utilizar os dois ou os três pontos, tem diferença:
- O uso de três pontos destaca explicitamente a divergência entre as branches, 
- Enquanto o uso dos dois pontos simplesmente compara os estados mais recentes.

<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




