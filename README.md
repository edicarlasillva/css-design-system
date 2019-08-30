# Framework CSS

### A design system

## Introdução

## Botões

Incluem estilos simples para diferentes tipos e tamanhos de botões. Adicione a classe `btn` aos elementos <button>.

```html
<button class="btn">Botão padrão</button>
```

### Botões primários

Para indicar que um botão representa uma ação principal, adicione `btn--primary` ao elemento `<button>` que já tenha `btn`.

```html
<button class="btn btn--primary">Botão primário</button>
```

### Botões personalizados

Existem classes btn--success e btn--error para sucesso (verde) e erro (vermelho).

```html
<button class="btn btn--success">Botão sucesso</button>
<button class="btn btn--error">botão erro</button>
```

### Button disabled

Adicione a classe btn--disabled ou o atributo disabled para o estilo desabilitado do botão.

```html
<button class="btn btn--disabled">botão desativado</button>
```

### Button sizes

Adicione as classes btn--small, btn--medium ou btn--large para tamanho de botão pequeno, médio ou grande.

```html
<button class="btn btn--small">Botão pequeno</button>
<button class="btn btn--medium">Botão médio</button>
<button class="btn btn--large">Botão grande</button>
```

### Outline buttons

```html
<button class="btn btn--outline-primary btn--medium">Botão outline</button>
<button class="btn btn--outline-success btn--medium">Botão outline</button>
<button class="btn btn--outline-error btn--medium">Botão outline</button>
```

### Icon label buttons

```css
.btn--icon-label
```

### Icon buttons

```css
.btn--icon
```
