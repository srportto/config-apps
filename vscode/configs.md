# Configuracoes para vscode
---
## Plugins
 
>Git History
>GitLens
>Markdown Preview Enhanced
>One Monokai Theme
>indent-rainbow
>Material Icon Theme
>Rainbow Brackets
>Rainbow CSV
>Reload


## Preferencias do editor
` No windows: ctrl + ,`
```
{
  // Abre qualquer instância do VSCode maximizada
  "window.newWindowDimensions": "maximized",

  // Habilita os breadcrumbs no editor do documento (exibe o caminho completo e permite interações)
  "breadcrumbs.enabled": true,
  "breadcrumbs.filePath": "on",
  "breadcrumbs.symbolPath": "off",
  "breadcrumbs.icons": false,
  "breadcrumbs.showFiles": true,
  "breadcrumbs.symbolSortOrder": "name", 

  // Fonte (tamanho)
  "editor.fontSize": 14,
  "editor.lineHeight": 24,
  "editor.letterSpacing": 0.6,
  "terminal.integrated.fontSize": 16,
  
  // Organizar imports automaticamente ao salvar + Formatar o arquivo
  "editor.formatOnSave": false,
  "editor.codeActionsOnSave": {
    "source.organizeImports": "explicit"
  },

  // Boas práticas
  "editor.tabSize": 2,
  "editor.rulers": [120, 180],

  // Detalhes
  "editor.cursorBlinking": "expand",
  "editor.renderLineHighlight": "gutter",

  // Desabilita a exibição do minimap do código na lateral direita
  "editor.minimap.enabled": false,

  // Estiliza o tamanho/formato da tab de um arquivo pinado
  "workbench.editor.pinnedTabSizing": "shrink",

  // Define 'Markdown' como a linguagem padrão do editor (todo novo arquivo será .md por padrão)
  "files.defaultLanguage": "markdown",

  // Aqui eu também posso utilizar a configuração de sempre abrir um novo arquivo em branco [Para exibir, é só abrir outro editor]
  "workbench.startupEditor": "newUntitledFile",

  // Quando você marca para não questionar ao deletar ou mover um arquivo no explorer (executa direto)
  "explorer.confirmDelete": false,
  "explorer.confirmDragAndDrop": false,

  // Preserva apenas os últimos 20 comandos executados na 'paleta de comandos', mas mantém o último valor digitado
  "workbench.commandPalette.history": 20,
  "workbench.commandPalette.preserveInput": true,

  // Mantém as pastas do File Explorer compactadas
  "explorer.compactFolders": false,
  "workbench.editor.enablePreview": false,

  // Controles básicos da busca do VSCode: sempre mostra minimizado e não busca em diretórios "auto-gerados" para otimizar a execução.
  "search.collapseResults": "alwaysCollapse",
  "search.exclude": {
    "**/.git": true,
    "**/*.code-search": true,
    "**/bower_components": true,
    "**/cypress/*": true,
    "**/node_modules": true,
    "**/storage": true,
    "package-lock.json": true
  },

  // Principais / Mais chamam atenção
  "workbench.sideBar.location": "left",
  "window.commandCenter": false,
  "workbench.statusBar.visible": true,
  "editor.fontFamily": "'Cascadia Code PL'",
  "editor.fontLigatures": "'ss01', 'ss02', 'ss03', 'ss19', 'ss20'",
  "workbench.layoutControl.enabled": false,
  "workbench.colorTheme": "One Monokai",
  "workbench.iconTheme": "material-icon-theme"
}
```
