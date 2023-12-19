# Resumos | Aula 10

### 🔍 O que é Conflito de Merge?

Esse problema ocorre quando duas pessoas fazem alterações simultâneas na mesma linha de código. Se uma delas tentar enviar essas mudanças, surge um conflito com as alterações feitas pela outra pessoa. Isso acontece porque o Git não consegue determinar automaticamente qual versão das alterações deve ser mantida. Em vez disso, ele gera um erro, pedindo que você escolha qual versão deseja manter. Por exemplo, se você editar um arquivo no GitHub e outro arquivo usando comandos de linha, ao tentar enviar para o repositório remoto, um erro será gerado, semelhante ao exemplo:

![exemplo de erro: conflito de merge](/img/exemplo-conflito-merge.jpg)


Antes de enviar alterações, é importante atualizar o repositório local usando "git pull" para sincronizar com as mudanças remotas. Se houver alterações conflitantes na mesma linha, será necessário uma resolução manual do conflito. Exemplo:

![exemplo de git pull](/img/conflito-merge-git-pull.jpg)


Como o Git não consegue escolher entre as alterações realizadas na mesma linha, ele salva o arquivo com as duas alterações, nos permitindo, então, alterar manualmente o arquivo e escolher a linha que queremos manter, exemplo:

![exemplo do arquivo antes da modificação](/img/arquivo-necessario-alteracao.jpg)

Após escolher qual modificação deseja manter, salve o arquivo:

![exemplo do arquivo depois de modificado](/img/arquivo-modificado.jpg)

Com o arquivo modificado podemos perceber que agora é reconhecido pelo "git status", e podemos seguir com o "git commit":

![exemplo do arquivo git status](/img/git-commit-apos-arquivo-modificado.jpg)

![exemplo do arquivo git git commit](/img/conflito-merge-git-pull-git-commit.jpg)

Agora ele nos permite enviar as modificações para nosso repositório remoto, com: “git push origin main”. Em outras palavras, estamos instruindo o Git a enviar as informações que estão na branch 'main' para o repositório remoto chamado 'origin':

![exemplo enviando arquivos com git push](/img/git-push.jpg)

E o problema foi resolvido;

---

<sub><b>Desenvolvido por: [Eloizi](https://github.com/Eloizi/gitHub-DIO) ❤️ - 2023</b></sub></a>




