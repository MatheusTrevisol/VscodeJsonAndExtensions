# VscodeJsonAndExtensions

VSCode config JSON and Extensions

/*Extensions*/

  - Brazilian Portuguese - Code Spell Checker (identificar pt-br)
  - Code Spell Checker - Check de palavras inglês - correções automáticas
  - Color Highlight
  - Fluent Icons
  - HTML CSS Support
  - JavaSscript (ES6) code snippets
  - Live Server
  - Material Icon Theme
  - Prettier Code Formatter
  - Prisma
  - Symbols
  - Tailwind CSS IntelliSense
  - vscode-styled-components
  
/*JSON*/

"[typescriptreact]": {
  "editor.defaultFormatter": "esbenp.prettier-vscode",
  "editor.formatOnSave": true,
  "editor.codeActionsOnSave": {
    "source.fixAll": "explicit"
  }
},
{
  "emmet.syntaxProfiles": {
    "javascript": "jsx"
  },
  "workbench.startupEditor": "newUntitledFile",
  "editor.fontSize": 14,
  "tabnine.experimentalAutoImports": true,
  "javascript.suggest.autoImports": true,
  "typescript.suggest.autoImports": true,
  "javascript.updateImportsOnFileMove.enabled": "always",
  "editor.rulers": [
    80,
    120
  ],
  "extensions.ignoreRecommendations": true,
  "typescript.tsserver.log": "off",
  "files.associations": {
    ".sequelizerc": "javascript",
    ".stylelintrc": "json",
    "*.tsx": "typescriptreact",
    ".env.*": "dotenv",
    ".prettierrc": "json"
  },
  "screencastMode.onlyKeyboardShortcuts": true,
  "cSpell.userWords": [
    "bootcamp",
    "chakra",
    "checkin",
    "checkins",
    "clsx",
    "Codegen",
    "datadog",
    "Datetime",
    "dayjs",
    "Dotenv",
    "esbuild",
    "fastify",
    "Fastify",
    "feedbackwidget",
    "ffprobe",
    "Hono",
    "IUGU",
    "jamjuree",
    "jupiter",
    "liveblocks",
    "LIVEBLOCKS",
    "middlewares",
    "mixpanel",
    "monaco",
    "nestjs",
    "omni",
    "Omni",
    "Onboarded",
    "pallas",
    "postgres",
    "postgresql",
    "prefetch",
    "reactflow",
    "roboto",
    "rocketseat",
    "rotion",
    "rsxp",
    "Sandpack",
    "shiki",
    "skylab",
    "sqlite",
    "supergraph",
    "svgr",
    "sympla",
    "textblock",
    "tiptap",
    "trpc",
    "TRPC",
    "tsup",
    "unfollow",
    "Unfollow",
    "unform",
    "Unform",
    "unmark",
    "upsert",
    "Usuario",
    "WEBPUSH"
  ],
  "editor.parameterHints.enabled": false,
  "editor.renderLineHighlight": "gutter",
  "cSpell.language": "en,pt",
  "editor.lineHeight": 22,
  "material-icon-theme.languages.associations": {
    "dotenv": "tune"
  },
  "typescript.updateImportsOnFileMove.enabled": "never",
  
  "material-icon-theme.files.associations": {
    "tsconfig.json": "tune",
    "*.webpack.js": "webpack",
    "*.proto": "3d",
    "ormconfig.json": "database"
  },
  "material-icon-theme.activeIconPack": "nest",
  "editor.suggestSelection": "first",
  "explorer.confirmDelete": false,
  "gitlens.codeLens.recentChange.enabled": false,
  "terminal.integrated.showExitAlert": false,
  "[prisma]": {
    "editor.formatOnSave": true
  },
  "terminal.integrated.env.osx": {
    "FIG_NEW_SESSION": "1"
  },
  "workbench.editor.labelFormat": "short",
  "editor.fontLigatures": true,
  "emmet.includeLanguages": {
    "javascript": "javascriptreact"
  },
  "liveshare.featureSet": "insiders",
  "material-icon-theme.folders.associations": {
    "adapters": "contract",
    "grpc": "pipe",
    "kube": "kubernetes",
    "main": "lib",
    "websockets": "pipe",
    "implementations": "core",
    "protos": "pipe",
    "entities": "class",
    "kafka": "pipe",
    "use-cases": "functions",
    "migrations": "tools",
    "schemas": "class",
    "useCases": "functions",
    "eslint-config": "tools",
    "typeorm": "database",
    "_shared": "shared",
    "mappers": "meta",
    "fakes": "mock",
    "modules": "components",
    "subscribers": "messages",
    "domain": "class",
    "protocols": "contract",
    "infra": "app",
    "view-models": "views",
    "presentation": "template",
    "dtos": "typescript",
    "http": "container",
    "providers": "include",
    "factories": "class",
    "repositories": "mappings"
  },
  "cSpell.enableFiletypes": [
    "!asciidoc",
    "!c",
    "!cpp",
    "!csharp",
    "!go",
    "!handlebars",
    "!haskell",
    "!jade",
    "!java",
    "!latex",
    "!php",
    "!pug",
    "!python",
    "!restructuredtext",
    "!rust",
    "!scala",
    "!scss"
  ],
  "editor.acceptSuggestionOnCommitCharacter": false,
  "explorer.compactFolders": false,
  "git.enableSmartCommit": true,
  "editor.accessibilitySupport": "off",
  "explorer.confirmDragAndDrop": false,
  "terminal.integrated.fontSize": 14,
  "terminal.integrated.fontFamily": "JetBrainsMono Nerd Font",
  "editor.codeActionsOnSave": {
    "source.fixAll.eslint": true,
    "source.addMissingImports": true
  },
  "eslint.validate": [
    "javascript",
    "javascriptreact",
    "graphql"
  ],
  "editor.semanticHighlighting.enabled": true,
  "breadcrumbs.enabled": true,
  "workbench.productIconTheme": "fluent-icons",
  "editor.fontFamily": "Fire Code",
  "gitlens.codeLens.authors.enabled": false,
  "editor.tabSize": 2,
  "security.workspace.trust.untrustedFiles": "newWindow",
  "files.exclude": {
    "**\/CVS": true,
    "**\/.DS_Store": true,
    "**\/.hg": true,
    "**\/.svn": true,
    "**\/.git": true,
    // "node_modules": true
  },
  "tabnine.experimentalAutoImports": true,
  "gitlens.codeLens.enabled": false,
  "workbench.iconTheme": "symbols",
  "polacode.transparentBackground": true,
  "polacode.target": "snippet",
  "editor.minimap.enabled": false,
  "update.mode": "start",
  "terminal.integrated.gpuAcceleration": "off",
  "terminal.integrated.defaultProfile.osx": "fish",
  "editor.defaultFormatter": "<another formatter>",
  "[javascript]": {
    "editor.defaultFormatter": "esbenp.prettier-vscode"
  },
  "[css]": {
    "editor.colorDecorators": true,
    "editor.suggest.showProperties": true
  },
  "workbench.editor.untitled.hint": "hidden",
  "liveServer.settings.donotShowInfoMsg": true,
  "window.commandCenter": true,
  "git.openRepositoryInParentFolders": "always",
  "workbench.colorTheme": "Default Dark+",
  "symbols.hidesExplorerArrows": false,
  "liveServer.settings.donotVerifyTags": true,
  "cSpell.language": "en, pt"
}
