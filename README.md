# Vestibular em Ação — v0.1 (fundação)

Plataforma educativa do projeto Vestibular em Ação (SIMAC 2027).

**Estado atual:** fundação visual + protótipo da preparação do Modo Gincana.
Guia, Desafios e Planejador ainda são páginas "em construção".

## Como executar
1. Instale o Visual Studio Code e a extensão **Live Server**.
2. Abra a pasta do projeto no VS Code.
3. Clique com o botão direito em `index.html` → **Open with Live Server**.

> Não abra o `index.html` com duplo clique: os navegadores bloqueiam módulos JavaScript em `file://`.

## Estrutura
- `css/variables.css` — cores, fontes e tamanhos da marca (tokens)
- `css/components.css` — botões, cards, campos, alertas, modal
- `js/data/` — dados oficiais (Kit da Gincana)
- `js/logic/` — regras sem HTML (testáveis)
- `js/pages/` — uma página por arquivo
- `js/components/` — peças reutilizáveis
- `assets/brand/` — logos (ícone V! provisório)

## Regras do projeto
- Nenhum dado pessoal ou de pesquisa é coletado.
- `localStorage` guarda apenas tema e rascunho da sessão (nomes coletivos de equipes).
- Sem chaves ou credenciais no código.
