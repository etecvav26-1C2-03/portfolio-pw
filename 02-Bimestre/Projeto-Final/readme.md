# F.E-GG

Repositório de organização e acesso aos projetos acadêmicos desenvolvidos ao longo do curso técnico em Desenvolvimento de Sistemas — ETEC Vasco Antônio Venchiarutti.

Projeto Web Final: uma página de apresentação do grupo, com um card por integrante levando à página individual de cada um.

## Sobre o grupo

O grupo foi formado em meados de 2026, quando os professores Ronildo e Madureira pediram que a turma de DS (atual 1C2) formasse grupos de 4 integrantes. Decidimos o nome **F.E-GG**, sigla para **F**elipe, **E**duardo, **G**abriel e **G**uilherme.

## Integrantes

| Nome | Função no projeto | GitHub |
|---|---|---|
| Eduardo Bargueiras | Front-End Developer — estrutura do HTML | [@Eduardo-Bargueiras](https://github.com/Eduardo-Bargueiras) |
| Felipe Barbosa Santos | Front-End Developer — CSS e estilização | [@felipebsa](https://github.com/felipebsa) |
| Gabriel Fernandes Barbarini | Front-End Developer — estrutura dos cards e responsividade | [@FeLaLost](https://github.com/FeLaLost) |
| Guilherme Lakonski | Escolha da paleta de cores e identidade visual | — |

## Identidade visual

A identidade do site é baseada na logo de uma raposa, com paleta em laranja (`#f2921d`), preto e branco/cinza.

## Estrutura do projeto

```
Projeto-Final/
├── img/                 # fotos dos integrantes e logo
├── style/
│   └── style.css        # CSS único do projeto, com variáveis de cor
└── templates/
    ├── index.html        # página principal (cabeçalho, sobre, cards, rodapé)
    ├── eduardo.html
    ├── felipe.html
    ├── gabriel.html
    └── guilherme.html
```

## Requisitos técnicos atendidos

- [x] HTML semântico (`header`, `main`, `section`, `footer`)
- [x] CSS em arquivo separado (`style/style.css`)
- [x] Variáveis CSS para as cores principais (`--raposa-laranja`, `--raposa-preto`, etc.)
- [x] Cards organizados com Flexbox (`.card`, `.header`, `.team-footer-container`)
- [x] Media query para celular, deixando os cards em coluna (`@media (max-width: 600px)`)
- [x] Cabeçalho com nome do grupo e frase curta
- [x] Seção "Quem somos" com um card por integrante (foto, nome, função e link para a página da pessoa)
- [x] Rodapé com contato (e-mail, GitHub, LinkedIn)

## Como visualizar

Basta abrir `templates/index.html` no navegador. Os caminhos de CSS e imagens são relativos (`../style/style.css`, `../img/...`), então a estrutura de pastas precisa ser mantida como está.

## Repositório

[github.com/etecvav26-1C2-03/portfolio-pw](https://github.com/etecvav26-1C2-03/portfolio-pw/tree/main/02-Bimestre/Projeto-Final)
