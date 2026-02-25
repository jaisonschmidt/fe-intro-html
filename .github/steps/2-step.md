## Step 2: Estrutura basica do HTML

Agora vamos montar a estrutura minima de um documento HTML.

### 📖 Teoria: Estrutura essencial

**O que são tags?** Tags são marcadores que definem elementos HTML. Elas ficam entre os sinais `<` e `>` e geralmente aparecem em pares: uma tag de abertura `<tag>` e uma de fechamento `</tag>`.

**Entendendo cada elemento:**

- `<!DOCTYPE html>` - Declara que este é um documento HTML5 (versão mais recente do HTML). Não é uma tag, mas uma instrução para o navegador.
- `<html>` - Elemento raiz que envolve todo o conteúdo da página. O atributo `lang="pt-BR"` indica o idioma para acessibilidade e mecanismos de busca.
- `<head>` - Contém metadados (informações sobre a página) que não aparecem visualmente, como título, charset e links para CSS.
- `<body>` - Contém todo o conteúdo visível da página: textos, imagens, links, etc.

📚 **Saiba mais:** [Anatomia de um documento HTML - MDN](https://developer.mozilla.org/pt-BR/docs/Learn/HTML/Introduction_to_HTML/Getting_started#anatomia_de_um_documento_html)

### ⌨️ Atividade: Monte o esqueleto

1. Abra o arquivo `index.html`.
1. Adicione a estrutura abaixo (voce pode ajustar a indentacao):

        ```html
        <!doctype html>
        <html lang="pt-BR">
            <head>
            </head>
            <body>
            </body>
        </html>
        ```

1. Salve, faca commit e envie para o GitHub.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Verifique se voce adicionou as tags de abertura e fechamento.
- O `lang` pode ser `pt-BR` ou outro idioma, nao tem problema.

</details>
