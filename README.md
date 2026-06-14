# Lemain Labs Theme

Extensão de tema para VS Code e Cursor inspirada na identidade visual da Lemain Labs.

## Tema

`Lemain Labs Ember` é um tema dark quente para quem quer sair do dark mode genérico e de temas como Dracula sem perder legibilidade. A paleta vem do projeto `../lemain-frontend` e do site [lemain-labs.com](https://lemain-labs.com).

## Paleta Base

- Fundo: `#070403`
- Superfície: `#0E0805`
- Superfície elevada: `#170D07`
- Borda: `#1E1209`
- Texto: `#FFFFFF`
- Texto suave: `#B8AFA6`
- Texto muted: `#7A7068`
- Acento: `#FF6E00`
- Acento glow: `#FF8B1F`
- Acento profundo: `#7A3500`

## Cobertura

- Interface do VS Code: editor, sidebar, tabs, panels, status bar, terminal, quick pick, notifications, notebooks, Git e diagnostics.
- Cursor: superfícies compartilhadas da activity bar, sidebar, panel, editor widgets e quick input usadas pela aba de agents quando expostas por tokens de tema.
- Syntax highlighting: JavaScript, TypeScript, JSX/TSX, Java, PHP, C, C++, Go, Python, JSON, CSS/SCSS, Markdown e linguagens baseadas em TextMate/semantic tokens.
- Destaques semânticos para variáveis, parâmetros, funções, métodos, classes, interfaces, structs, enums, propriedades, keys, constantes, strings, números, comentários, operadores e decorators.

## Desenvolvimento Local

1. Instale dependências:

```sh
npm install
```

2. Abra este repositório no VS Code ou Cursor.

3. Pressione `F5` para iniciar uma janela de Extension Development Host.

4. Selecione `Lemain Labs Ember` em `Preferences: Color Theme`.

## Empacotamento

```sh
npm run package
```

O comando gera um arquivo `.vsix` instalável localmente.

## Publicação

```sh
npm run publish
```

Antes de publicar, confirme o `publisher` em `package.json` com o publisher real do Marketplace.
