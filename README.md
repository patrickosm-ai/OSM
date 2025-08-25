# Site da Banda Os Marés

Site oficial da banda de hardcore "Os Marés" para divulgação de links das músicas.

## Arquivos

- `index.html` - Estrutura HTML do site
- `styles.css` - Estilos CSS e animações
- `script.js` - Funcionalidades JavaScript
- `README.md` - Este arquivo de instruções

## Como usar

1. **Baixe todos os arquivos** para a mesma pasta
2. **Abra o arquivo `index.html`** no seu navegador
3. **Para colocar online**, faça upload de todos os arquivos para seu servidor/hosting

## Personalização

### Trocar links das músicas
No arquivo `index.html`, procure pelas linhas com `onclick="openLink('...')` e substitua as URLs:

```html
<!-- Exemplo -->
<div class="music-card" onclick="openLink('https://open.spotify.com/artist/SEUARTISTA')">
```

### Trocar redes sociais
No arquivo `index.html`, procure pela seção `social-links` e adicione os links reais:

```html
<a href="https://facebook.com/suabanda" class="social-link">📘</a>
<a href="https://instagram.com/suabanda" class="social-link">📷</a>
<a href="https://twitter.com/suabanda" class="social-link">🐦</a>
```

### Modificar texto sobre a banda
No arquivo `index.html`, procure pela seção `bio-text` e personalize o conteúdo.

### Alterar cores
No arquivo `styles.css`, você pode modificar as cores principais:
- Cor principal: `#ff4757` (vermelho)
- Cor secundária: `#c44569` (rosa escuro)
- Fundo: gradiente de preto

## Recursos

- Design responsivo (funciona em celular e desktop)
- Animações suaves
- Efeitos de hover interativos
- Partículas animadas no fundo
- Compatível com todos os navegadores modernos

## Dicas

- **Para melhor performance**: Otimize as imagens antes de adicionar
- **Para SEO**: Adicione meta tags no `<head>` do HTML
- **Para analytics**: Adicione Google Analytics no final do `<body>`

## Suporte

Para modificações mais avançadas, você pode:
- Contratar um desenvolvedor web
- Usar ferramentas como WordPress
- Aprender mais sobre HTML, CSS e JavaScript
