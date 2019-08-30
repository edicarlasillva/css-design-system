# Framework CSS

### Design System

## Introdução

## Botões

Incluem estilos simples para diferentes tipos e tamanhos de botões. Adicione a classe `btn` aos elementos:

- <a>
- <button>
- <input type="submit">
- <input type="reset">.

```html
<button class="btn">Botão padrão</button>
```

**Você sempre precisará especificar cor e tamanho para obter um botão completo.**

```html
<!-- Exemplo de um botão completo -->
<button class="btn btn--primary btn--medium">Botão padrão</button>
```

### Cores

Para indicar que um botão representa uma ação principal, adicione `btn--primary` ao elemento `<button>` que já tenha a classe `btn`. Também existem `btn--success` e `btn--error` para sucesso (verde) e erro (vermelho). Você deve exibir apenas uma cor de cada vez.

```html
<button class="btn btn--primary">Botão primário</button>
<button class="btn btn--success">Botão sucesso</button>
<button class="btn btn--error">Botão erro</button>
```

### Tamanhos

Adicione as classes btn--small, btn--medium ou btn--large para tamanho de botão pequeno, médio ou grande.

```html
<button class="btn btn--small">Botão pequeno</button>
<button class="btn btn--medium">Botão médio</button>
<button class="btn btn--large">Botão grande</button>
```

### Desativado

Adicione a classe `btn--disabled` ou o atributo `disabled` para o estilo desabilitado do botão.

```html
<button class="btn btn--disabled btn--medium">Botão desativado</button>
```

### Contorno

```html
<button class="btn btn--outline-primary">Botão outline</button>
<button class="btn btn--outline-success">Botão outline</button>
<button class="btn btn--outline-error">Botão outline</button>
```

### Icon label buttons

```css
.btn--icon-label
```

### Icon buttons

```css
.btn--icon
```
