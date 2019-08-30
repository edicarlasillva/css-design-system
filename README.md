# Framework CSS

### Design System

## Introdução

## Botões

Incluem estilos simples para diferentes tipos e tamanhos de botões. Adicione a classe `btn` aos elementos:

- `<a>`
- `<button>`
- `<input type="submit">`
- `<input type="reset">`

```html
<button class="btn">Botão padrão</button>
```

**Você sempre precisará especificar cor e tamanho para obter um botão completo.**

```html
<!-- Exemplo de um botão completo -->
<button class="btn btn--primary btn--medium">Botão padrão</button>
```

### Cores

Para indicar que um botão representa uma ação principal, adicione `btn--primary` ao elemento `<button>` que já tenha a classe `btn`. Também existem `btn--success` e `btn--error` para sucesso (verde), erro (vermelho) ou advertência (amarelo). Você deve exibir apenas uma cor de cada vez.

```html
<button class="btn btn--primary">Botão primário</button>
<button class="btn btn--success">Botão sucesso</button>
<button class="btn btn--error">Botão erro</button>
<button class="btn btn--warning">Botão advertência</button>
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
<button class="btn btn--primary btn--disabled">
  Botão desativado
</button>
```

### Contorno

Para remover a cor de fundo de um botão, adicione a classe `btn--outline-*`.

**\* deve ser substituido pela cor do contorno**:

- primary
- success
- error
- warning

```html
<button class="btn btn--outline-primary">Botão outline primário</button>
<button class="btn btn--outline-success">Botão secesso</button>
<button class="btn btn--outline-error">Botão erro</button>
<button class="btn btn--outline-warning">Botão advertência</button>
```

### Ícone

Você pode adicionar um ícone ao botão com a classe `btn--icon-label`.

```html
<button class="btn btn--outline-primary btn--medium btn--icon-label">
  <img src="images/calendar.svg" class="icon icon--size-small" />
  Botão com ícone
</button>
```

### Botão ícone

Você pode ter um botão apenas com o ícone desejado, use a classe `btn--icon`.

```css
.btn--icon-label
```

### Ícone como botão

```css
.btn--icon
```
