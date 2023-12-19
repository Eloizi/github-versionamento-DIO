# Resumos | Aula 12

### Clonando uma Branch específica:


Vamos supor que existe um repositório que contém várias branches, mas você deseja clonar apenas uma delas. Como deve proceder?

Para isso, acesse o GitHub e copie o link do repositório desejado. Por exemplo:

![clonando repositorio do GitHub](/img/github-clonandoRepo.jpg)


Após isso, no Git Bash, utilizamos o comando git clone para clonar o repositório, colamos o link do repositório desejado e, em seguida, usamos a opção --branch para especificar qual branch desse repositório queremos clonar. O parâmetro --single-branch indica que queremos clonar apenas essa branch. O comando final é semelhante a este exemplo:

```
git clone https://github.com/Eloizi/Hello-Word --branch teste --single-branch
```

 🚨 Atenção: Se você não especificar qual branch deseja clonar, o Git irá clonar apenas a branch principal


<br>

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




