 # **ATIVIDADE-WAI-ARIA**

## Questão 1 - O que é WAI-ARIA

### O que é
O *WAI-ARIA* é um conjunto de atributos que torna sites mais acessíveis. Sua principal função é complementar informações extras, permitindo que elementos como menus, botões, formulários e janelas interativas sejam corretamente interpretados.

### Funcionalidade
sua principal utilidade é em suma, melhorar a experiência e acessibilidade de sites e etc, ajudando tecnologias assistivas, como leitores de tela, a entenderem a estrutura e o comportamento dos elementos da página.

### Quem são os principais beneficiados?

Os principais beneficiados são pessoas com deficiência, especialmente usuários com deficiência visual que utilizam leitores de tela. Além disso, pessoas com limitações motoras, cognitivas ou outras necessidades de acessibilidade também são favorecidas, tornando a navegação mais inclusiva e eficiente.

## Questão 2 - Analise o trecho de código abaixo:

```html
<button
    class="navbar-toggler"
    type="button"
    aria-controls="menuPrincipal"
    aria-expanded="false"
    aria-label="Abrir menu">
    Menu
</button>
```

Responda:

## a) Qual é a função do atributo aria-controls?

**R:** A função do atributo **aria-controls** é indicar que o botão controla o elemento com o identificador *MenuPrincipal*.

## b) O que informa o atributo aria-expanded?

**R:** O atributo **aria-expanded** informa se o elemento está expandido ou recolhido. No caso desse código, o *false* indica que o menu está fechado.

## c) Qual é a importância do atributo aria-label para usuários que utilizam leitores de tela?

**R:** O **aria-label** fornece uma informação(no caso o "Abrir menu") para o leitor de tela transformar em audio ou em uma linha braille

## Questão 3 - Reflexão

Muitas vezes é possível construir uma interface utilizando apenas elementos HTML semânticos, como <button>, <nav> e <main>. Entretanto, em algumas situações, é necessário utilizar atributos do WAI-ARIA.

### Explique por que o WAI-ARIA não substitui o HTML semântico e descreva uma situação em que seu uso seja necessário para melhorar a acessibilidade de uma página web.

### **R:** O WAI-ARIA não substitui o HTML semântico porque ele funciona como um complemento, adicionando informações de acessibilidade quando o HTML sozinho não é suficiente
