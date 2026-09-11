# Meta-análise no R

Código-fonte do livro publicado em <https://metanalise-r.github.io>.

## Gerar o site no computador

Requer R e Quarto (o Quarto já vem com o RStudio).

```sh
quarto preview   # abre uma prévia no navegador, atualizando a cada alteração
quarto render    # gera o site completo em _book/
```

## Publicar

```sh
quarto publish gh-pages
```
