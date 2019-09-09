# Cristal

### Framework CSS

## Introdução

## Botões

Incluem estilos simples para diferentes tipos e tamanhos de botões. Adicione a classe `c-btn` aos elementos:

- `<a>`
- `<button>`
- `<input type="submit">`
- `<input type="reset">`

```html
<button class="c-btn">Botão padrão</button>
```

**Você sempre precisará especificar cor e tamanho para obter um botão completo.**

```html
<!-- Exemplo de um botão completo -->
<button class="c-btn c-btn--primary c-btn--medium">Botão padrão</button>
```

### Cores

Para indicar que um botão representa uma ação principal, adicione `c-btn--primary` ao elemento `<button>` que já tenha a classe `c-btn`. Também existem `c-btn--success` e `c-btn--error` para sucesso (verde), erro (vermelho) ou advertência (amarelo). Você deve exibir apenas uma cor de cada vez.

```html
<button class="c-btn c-btn--primary">Botão primário</button>
<button class="c-btn c-btn--success">Botão sucesso</button>
<button class="c-btn c-btn--error">Botão erro</button>
<button class="c-btn c-btn--warning">Botão advertência</button>
```

### Tamanhos

Adicione as classes btn--small, btn--medium ou btn--large para tamanho de botão pequeno, médio ou grande.

```html
<button class="c-btn c-btn--small">Botão pequeno</button>
<button class="c-btn c-btn--medium">Botão médio</button>
<button class="c-btn c-btn--large">Botão grande</button>
```

### Desativado

Adicione a classe `c-btn--disabled` ou o atributo `disabled` para o estilo desabilitado do botão.

```html
<button class="c-btn c-btn--primary c-btn--disabled">
  Botão desativado
</button>
```

### Contorno

Para remover a cor de fundo de um botão, adicione a classe `c-btn--outline-*`.

**\* deve ser substituido pela cor do contorno**:

- primary
- success
- error
- warning

```html
<button class="c-btn c-btn--outline-primary">Botão outline primário</button>
<button class="c-btn c-btn--outline-success">Botão secesso</button>
<button class="c-btn c-btn--outline-error">Botão erro</button>
<button class="c-btn c-btn--outline-warning">Botão advertência</button>
```

### Ícone

Você pode adicionar um ícone ao botão com a classe `c-btn--icon-label`.

```html
<button class="c-btn c-btn--outline-primary c-btn--medium c-btn--icon-label">
  <img src="images/calendar.svg" class="c-icon c-icon--size-small" />
  Botão com ícone
</button>
```

### Botão ícone

Você pode ter um botão apenas com o ícone desejado, use a classe `c-btn--icon`.

```css
.c-btn--icon-label
```

### Ícone como botão

```css
.c-btn--icon
```
