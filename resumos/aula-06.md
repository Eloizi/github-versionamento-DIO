
# Resumos | Aula 06

Para remover um arquivo do espaço de preparação podemos utilizar o git reset, e o git restore, exemplo: suponhamos que temos 2 arquivos, arquivo-01.md e arquivo-02.md, e demos um:

```
git add .
```

Adicionando todos os arquivos para o espaço de preparação, porém mudamos de ideia e não queremos dar commit no arquivo-02 ainda. Para reverter essa operação e tirar esse arquivo-02 do espaço de preparação temos duas formas:

```
git reset arquivo-02.md

ou

git restore --staged arquivo-02.md
```
Para confirmar se o arquivo saiu do espaço de preparação damos um "git status";

Segue um exemplo prático:


![Exemplo da utilização do git restore --stage](https://www.golinuxcloud.com/wp-content/uploads/git-restore-staged.png)

<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




