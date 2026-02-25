## Step 7: Insira uma imagem

Vamos adicionar uma imagem simples usando um placeholder.

### 📖 Teoria: A tag `img`

A tag `<img>` exibe imagens na página web. É uma tag de **auto-fechamento** (não precisa de `</img>`).

**Atributos obrigatórios:**
- `src` (_source_) - Caminho ou URL da imagem
- `alt` (_alternative text_) - Texto alternativo que descreve a imagem

**Importância do `alt`:**
- **Acessibilidade:** Leitores de tela leem o texto `alt` para pessoas com deficiência visual
- **SEO:** Motores de busca usam o `alt` para entender o conteúdo da imagem
- **Fallback:** Aparece quando a imagem não carrega

**Outros atributos úteis:**
- `width` e `height` - Dimensões da imagem
- `loading="lazy"` - Carregamento sob demanda (melhora performance)

📚 **Saiba mais:** [Elemento img - MDN](https://developer.mozilla.org/pt-BR/docs/Web/HTML/Element/img)

### ⌨️ Atividade: Imagem do placehold.co

1. No `body`, adicione uma imagem do site `placehold.co`.
1. Inclua o atributo `alt` com uma descricao curta.
1. Exemplo:

   ```html
   <img src="https://placehold.co/600x400" alt="Imagem de exemplo">
   ```

1. Salve, faca commit e envie para o GitHub.

<details>
<summary>Having trouble? 🤷</summary><br/>

- Verifique se o `src` contem `placehold.co`.
- O `alt` e obrigatorio para acessibilidade.

</details>
