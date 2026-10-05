# Retro Discos

Site expositivo e responsivo para uma loja retrô especializada em discos de vinil.

O projeto foi desenvolvido como atividade acadêmica com foco em apresentação de produtos, organização por gêneros musicais, preços estimados e contato direto com a loja.

## Funcionalidades

- Página inicial com identidade visual retrô.
- Menu de gêneros musicais.
- Catálogo de discos com fotos ilustrativas.
- Filtro por gênero.
- Campo de busca por artista, álbum ou gênero.
- Preços estimados para os produtos.
- Botão **Entre em contato!** direcionado ao WhatsApp.
- Cabeçalho com nome e logotipo da loja.
- Rodapé com espaço para o endereço comercial.
- Menu mobile.
- Layout responsivo para celulares, tablets, notebooks e monitores maiores.
- Boas práticas básicas de acessibilidade, incluindo navegação por teclado, estados de foco e respeito à preferência de redução de movimento.

## Tecnologias utilizadas

- HTML5
- CSS3
- JavaScript

O projeto não utiliza banco de dados e pode ser executado diretamente no navegador.

## Estrutura

```text
Retro/
├── assets/
│   └── logo.svg
├── css/
│   └── style.css
├── js/
│   └── script.js
├── index.html
└── README.md
```

## Como executar

1. Clone o repositório.
2. Abra a pasta do projeto no VS Code.
3. Abra o arquivo `index.html` no navegador.

Também é possível utilizar a extensão **Live Server** no VS Code.

## Configurações antes da entrega

### WhatsApp

No arquivo `js/script.js`, altere:

```js
const STORE_WHATSAPP = "5531999999999";
```

Use o número real da loja no formato:

```text
55 + DDD + número
```

Exemplo de estrutura: `5531XXXXXXXXX`.

### Endereço

No rodapé do arquivo `index.html`, substitua:

```text
Endereço da loja: atualize aqui com o endereço comercial completo.
```

pelo endereço real da loja.

## Gêneros incluídos

- Rock
- Pop Rock
- Jazz
- Música Clássica
- MPB
- Sertanejo
- Sertanejo Universitário

O catálogo pode ser ampliado facilmente adicionando novos cards em `index.html`.

## Observações

Os preços apresentados são estimados e possuem finalidade expositiva. As imagens utilizadas no catálogo são ilustrativas e provenientes do Unsplash.

---

Projeto desenvolvido para fins educacionais.
