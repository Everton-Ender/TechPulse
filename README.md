# TechPulse — Portal de Notícias de Tecnologia

Projeto acadêmico de Front-End desenvolvido com HTML5 e CSS3.

## Como executar
1. Baixe ou clone o repositório.
2. Abra a pasta `TechPulse`.
3. Abra o arquivo `index.html` em um navegador.

Não é necessário instalar dependências ou configurar servidor.

## Tecnologias e serviços utilizados
- **HTML5:** estrutura e organização semântica do conteúdo.
- **CSS3:** aparência, cores, tipografia, espaçamentos e responsividade.
- **SVG:** ilustração vetorial local, leve e escalável.
- **Media Queries:** adaptação do layout para telas menores.
- **Navegador web:** execução e visualização do portal.

## Justificativas de design
### Cores
- `#0b1220` e `#101a2b`: tons escuros usados como fundo, criando contraste e identidade visual tecnológica.
- `#35d0ba`: verde-água para destaques e ações.
- `#f3f6fc`: texto principal claro, facilitando a leitura.
- `rgba(255, 255, 255, 0.12)`: bordas discretas com transparência.

### Tipografia
Foi utilizada a família Arial, com alternativas Helvetica e sans-serif. É uma tipografia comum, de boa legibilidade.
Os títulos possuem tamanhos maiores e pesos destacados para estabelecer hierarquia. O texto está alinhado à esquerda nas áreas de conteúdo e centralizado no rodapé.

### Espaçamentos e Box Model
- `padding`: cria espaço interno nos cartões, botão, cabeçalho e seções.
- `margin`: separa elementos e centraliza o container com `margin: 0 auto`.
- `border`: delimita cartões, botão e áreas da página.
- `border-radius`: suaviza os cantos de cartões e botão.
- `box-sizing: border-box`: facilita o cálculo das dimensões dos elementos.

## Acessibilidade e semântica
O documento utiliza `header`, `nav`, `main`, `section` e `footer`. Há um título principal `h1`, títulos secundários `h2`, texto com `strong`, lista de tecnologias, link de ação e imagem com texto alternativo (`alt`). A navegação possui um rótulo acessível.

## Responsividade
A página usa Grid e uma Media Query em `max-width: 700px`. Em telas menores, o conteúdo passa para uma coluna, o menu pode quebrar linha e os cartões ficam empilhados.

## Sitemap Visual e taxonomia
A hierarquia representa a organização de conteúdo do portal:

```text
TechPulse
└── Página Inicial
    ├── Notícias
    │   ├── Inteligência Artificial
    │   ├── Desenvolvimento Web
    │   └── Games e Hardware
    ├── Tecnologias
    │   ├── IA e Automação
    │   ├── Programação
    │   └── Equipamentos
    └── Sobre
        ├── O Portal
        └── Contato
```

A página inicial é o nível principal. As categorias agrupam assuntos relacionados e as subcategorias detalham cada tema. Essa taxonomia facilita a navegação e permite ampliar o portal futuramente.

## Estrutura de arquivos
```text
TechPulse/
├── index.html
├── css/
│   └── style.css
├── images/
│   └── tecnologia.svg
└── README.md
```
