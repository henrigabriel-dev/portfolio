# Projeto HTML + SCSS + Bootstrap

## 📋 Estrutura do Projeto

```
port/
├── index.html          # Página principal
├── css/
│   └── style.css      # CSS compilado (gerado automaticamente)
├── scss/
│   ├── style.scss     # Arquivo SCSS principal
│   ├── _variables.scss # Variáveis SCSS
│   └── _mixins.scss   # Mixins SCSS
├── .vscode/
│   └── settings.json  # Configurações do VS Code
└── README.md
```

## 🚀 Como Começar

### Compilar SCSS

#### Opção 1: Extensão Live Sass Compiler (Recomendado)

1. Instale a extensão "Live Sass Compiler" no VS Code
2. Abra o arquivo `scss/style.scss`
3. Clique em "Watch Sass" na barra de status inferior
4. O CSS será compilado automaticamente em `css/style.css`

#### Opção 2: Compilador Standalone

Baixe o Dart Sass standalone:
- https://github.com/sass/dart-sass/releases

Execute:
```bash
sass --watch scss:css
```

## 🎨 Recursos Incluídos

- ✅ Bootstrap 5.3.2 via CDN
- ✅ Estrutura SCSS modular (variáveis, mixins)
- ✅ Layout responsivo
- ✅ Navbar, footer e estrutura básica
- ✅ CSS já compilado para começar imediatamente

## 📝 Uso

Abra `index.html` no navegador ou use uma extensão como "Live Server" no VS Code.

## 🎯 Próximos Passos

1. Personalize as variáveis em `scss/_variables.scss`
2. Adicione seus estilos em `scss/style.scss`
3. Crie novos arquivos SCSS parciais conforme necessário
4. Compile o SCSS para CSS
