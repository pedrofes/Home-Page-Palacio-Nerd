# Palácio Nerd

## Sobre o projeto

Este é o segundo projeto de uma trilha de estudos relacionada às linguagens HTML e CSS. No projeto em questão, foi desenvolvida uma página inicial para um site de cultura pop e entretenimento de Pedro Fonseca, o "Palácio Nerd".

O objetivo do projeto foi praticar a construção de páginas web utilizando HTML e CSS, além de aplicar conceitos de responsividade, acessibilidade e interatividade com JavaScript.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript
- Google Fonts

## Funcionalidades

- Página inicial para um site de cultura pop e entretenimento.
- Menu de navegação responsivo.
- Menu hambúrguer para dispositivos móveis.
- Efeitos de interação com hover em elementos da página.
- Layout responsivo para diferentes tamanhos de tela.
- Navegação pelo teclado no menu.
- Recursos de acessibilidade no menu hambúrguer.

## Responsividade

O projeto foi desenvolvido para se adaptar de maneira responsiva a diferentes formatos de tela, incluindo desktop, tablet e dispositivos móveis.

### Desktop

Em telas maiores, o conteúdo é apresentado em colunas e o menu de navegação permanece expandido horizontalmente.

### Tablet

Em telas intermediárias, o layout é ajustado para aproveitar melhor o espaço disponível, mantendo a organização das notícias, categorias, conteúdo em destaque e rodapé.

### Mobile

Em dispositivos móveis, o conteúdo é reorganizado verticalmente. O menu de navegação é substituído por um menu hambúrguer e as notícias, categorias e demais seções são adaptadas à largura reduzida da tela.

## Acessibilidade

Tendo em vista o cumprimento de critérios de acessibilidade, as seguintes medidas foram incorporadas ao código:

- Inserção de textos alternativos (`alt`) nas imagens.
- Utilização de HTML semântico, com elementos como `header`, `nav`, `main`, `section` e `footer`.
- Definição da hierarquia de títulos com `h1`, `h2` e `h3`.
- Inclusão de um título principal (`h1`) para identificação da página.
- Utilização de `aria-label` no botão do menu hambúrguer.
- Utilização de `aria-controls` para indicar qual elemento é controlado pelo botão.
- Utilização de `aria-expanded` para indicar se o menu está aberto ou fechado.
- Possibilidade de navegação pelo menu utilizando o teclado.

## Estrutura do projeto

```text
palacio-nerd/
├── assets/
│   └── images/
├── index.html
├── style.css
└── README.md