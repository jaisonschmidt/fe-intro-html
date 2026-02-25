## Step 6: Crie um link

Vamos adicionar um link para um site externo.

### 📖 Teoria: A tag `a`

A tag `<a>` (de _anchor_, âncora) cria hiperlinks que conectam páginas web. É a base da navegação na internet!

**Atributos principais:**
- `href` (obrigatório) - Define o destino do link (URL)
- `target="_blank"` - Abre o link em nova aba
- `rel="noopener"` - Segurança ao usar `target="_blank"`
- `title` - Texto que aparece ao passar o mouse sobre o link

**Exemplo completo:**
```html
<a href="https://exemplo.com" target="_blank" rel="noopener">Visite o site</a>
```

📚 **Saiba mais:** [Elemento a - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/a)

### ⌨️ Atividade: Link para atitus.edu.br

1. No `body`, adicione um link para `https://atitus.edu.br`.
1. Exemplo:

   ```html
   <a href="https://atitus.edu.br">Visite a Atitus</a>
   ```

1. Salve, faca commit e envie para o GitHub.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Verifique se o `href` aponta para `atitus.edu.br`.
- O texto do link pode ser o que voce quiser.

</details>
