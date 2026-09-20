# Portfólio Pessoal — DaisyUI

Página pessoal desenvolvida como atividade prática do módulo de **DaisyUI**, utilizando **Tailwind CSS** e os componentes da biblioteca DaisyUI.

O objetivo do projeto é apresentar um pouco sobre mim, minhas habilidades e alguns projetos que desenvolvi durante meus estudos em Informática para Internet.


## Tecnologias utilizadas

- HTML5
- Tailwind CSS
- DaisyUI
- JavaScript


## Componentes DaisyUI utilizados

### Navbar
Utilizado no topo da página para criar a navegação entre as principais seções:

- Sobre
- Projetos
- Contato

Também foi utilizado um botão para alternar entre os temas claro e escuro.

### Hero
Utilizado na primeira seção da página para apresentar meu nome, minha área de estudo e os principais botões de ação.

### Buttons (`btn`)
Foram utilizados diferentes estilos de botões, como:

- `btn-primary`
- `btn-outline`
- `btn-ghost`

Eles aparecem na navegação, nos links de projetos e nas ações da página.

### Cards (`card`)
Os cards foram utilizados principalmente na seção de projetos e na apresentação das habilidades.

Cada card possui um `card-body`, seguindo a estrutura do DaisyUI.

### Badges (`badge`)
Os badges são utilizados para destacar informações como:

- Infoweb
- Desenvolvimento Web
- UI/UX
- HTML
- CSS
- JavaScript
- Python
- Git

Foram utilizadas diferentes variações de badges para criar uma hierarquia visual.

### Input
Na seção de contato foi criado um formulário utilizando campos de:

- Nome
- E-mail
- Mensagem

### Alert
Também foi utilizado um `alert` para informar que o formulário de contato é demonstrativo.


## Escolha do Header

Foi escolhido o componente **Navbar** porque ele facilita a navegação entre as diferentes partes da página.

Além disso, a navbar permite apresentar a identidade visual do portfólio logo no início e funciona de maneira responsiva em dispositivos menores.

O projeto também utiliza uma seção Hero logo abaixo da navbar para apresentar as principais informações de forma mais visual.


## Ajustes utilizando Tailwind CSS

Além dos componentes prontos do DaisyUI, foram utilizadas classes utilitárias do Tailwind CSS para personalizar o visual da página.

Entre os principais ajustes estão:

- Cores em tons de rosa;
- Espaçamentos;
- Tamanhos de texto;
- Layout responsivo;
- Bordas arredondadas;
- Sombras;
- Efeitos de hover;
- Organização em grids;
- Alinhamento dos elementos;
- Adaptação para telas menores.

A ideia foi manter os componentes do DaisyUI, mas personalizar a página para criar uma identidade visual própria.


## Temas claro e escuro

A página possui dois temas:

- ☀️ Tema claro
- 🌙 Tema escuro

A troca pode ser feita pelo botão localizado na navbar.

O tema escolhido também fica salvo no navegador utilizando `localStorage`, permitindo que a preferência seja mantida quando a página for aberta novamente.

A implementação utiliza o atributo:

```html
data-theme="light"