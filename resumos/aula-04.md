
# Resumos | Aula 04

### 🔁 Revertendo Modificações:
Caso tenha feito a modificação e realizado o commit, o procedimento para reverter a modificação deve ser feito utilizando o comando git reset, selecionando entre as opções:

```diff
+ --soft

+ --mixed ou 

--hard
```


 |opções| Descrição|
 |------|----------|
 |--soft| Reverte o commit e deixa os arquivos no status stated;
 |--mixed| Reverte o commit e deixa os arquivos no status modified; (Comportamento padrão do git reset)|
 |--hard| Reverte o commit e ignora todas as modificações feitas.|
 
 <br>

## 🚶‍♀️ Passo 01

Para desfazer um commit, primeiro através do git log, ou git show -s, copie o hash do commit que você quer retornar, exemplo:

![Copiando hash de um commit](https://linuxhint.com/wp-content/uploads/2023/01/word-image-283970-2.png)


```
git log
```
- é usado para visualizar o histórico de commits em um repositório Git. Ele exibe uma lista de commits, começando pelo commit mais recente e indo em direção ao passado.
```
git show -s 
```
- git show: Este é o comando principal que é usado para exibir informações sobre objetos Git, a opção "-s" significa "sintético" (ou "sucinto"), exibindo as informações do commit de forma resumida. 

<br>

---
## 🚶‍♀️🚶 Passo 02
Após escolher uma das três formas de reset, só dar sequência no comando:

```
$ git reset --soft (cole aqui o hash do commit)
```

## 🚶‍♀️🚶🚴‍♀️ Passo 03

Após o comando, ele retorna os arquivos para o estado em que estavam no “commit especificado pelo hash” e colocou os arquivos agora no estage area → estado de preparação.

Como ainda não demos o git commit essa alteração não foi salva, então agora só darmos sequência (caso esteja tudo correto) e salvar o processo com:

```
$ git commit -m “mensagem do commit”
```


---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>






