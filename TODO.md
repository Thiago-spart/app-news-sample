# TO-DO

Objetivo: Desenvolver um aplicativo mobile para Android que consome uma API de notícias e
exibe as manchetes em uma lista, com funcionalidades básicas de busca e detalhamento.

## Requisitos

### Tela inicial (Lista de Notícias)

- [] [Lista de notícias com manchetes de notícias](#intens_manchete).
- [] Scroll infinito ou paginação básica.
- [] Campo de busca para filtrar notícias por palavra-chave.

#### intens_manchete

- [] Título
- [] Imagem de destaque(se houver)
- [] Data de publicação
- [] Fonte (nome do site/jornal)

### Tela de detalhes

Ao clicar em uma notícia

- [] Titulo completo
- [] Imagem de destaque(se houver)
- [] Conteúdo/resumo
- [] Link para a noticia original

### Funcionalidades opcionais

- [] Favoritos salvar noticias favoritas localmente
- [] Filtrar noticias por categoria (ex: business, entertainment, health, science, sports, technology)
- [] cache básico para exibir noticias já carregas sem conexão

## Tecnologias

- React Native Expo
- Gerenciamento de estado Zustand or Tanstack store
- Styled Components
- Axios e fetch

### API Sugerida

- GNews
