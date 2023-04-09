# Padrão para mensagens de commit na Rede_

Formato: `<tipo>(<escopo>): <resumo>`

`<escopo>` é opcional

## Exemplo

```
feat: create /getUsers route
^--^  ^--------------------^
|     |
|     +-> Resumo das modificações feitas, no presente e em inglês.
|
+-------> Tipo do commit: chore, docs, feat, fix, refactor, style, or test.
```

No geral, é bom não deixar muitas alterações para serem feitas no mesmo commit, se você está na dúvida de qual tipo usar na mensagem, provavelmente é porque ele poderia ser separado em commits diferentes.

**O que significa cada tipo de commit?**

### Principais
- `feat`: (vem de 'feature', significa que estamos adicionando uma funcionalidade nova ao código)
- `fix`: (arrumando algum bug ou problema do código)
- `refactor`: (refatoração do código, mudar nomes de arquivo, modularizar o código)

### Extras
- `docs`: (mudanças na documentação)
- `style`: (mudanças na identação, adicionar ponto e vírgulas, sem alteração do funcionamento do código)
- `test`: (adicionar novos testes ou alterar os presentes)
- `chore`: (indica mudanças no projeto que não afetem o sistema ou arquivos de testes, mudanças de desenvolvimento.)

### References:

- https://medium.com/linkapi-solutions/conventional-commits-pattern-3778d1a1e657
- https://gist.github.com/joshbuchea/6f47e86d2510bce28f8e7f42ae84c716#file-semantic-commit-messages-md
- https://www.conventionalcommits.org/
- https://seesparkbox.com/foundry/semantic_commit_messages
- http://karma-runner.github.io/1.0/dev/git-commit-msg.html