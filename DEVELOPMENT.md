# 📋 Guia de Desenvolvimento - Personal Workspace

## Começando o Desenvolvimento

Este arquivo contém dicas e guidelines para desenvolver ou expandir o Personal Workspace Dashboard.

## 📐 Estrutura CSS

O projeto utiliza **CSS Custom Properties** (variáveis CSS) para manter consistência:

```css
:root {
  --color1: #ffffff;      /* Branco */
  --color2: #a1ac88;      /* Verde Musgo */
  --color3: #757575;      /* Cinza */
  --color4: #464d70;      /* Azul Acinzentado */
  --color5: #000000;      /* Preto */
  --spacing: 20px;
  --border-radius: 10px;
  --transition: all 0.3s ease;
}
```

Use essas variáveis ao adicionar novos estilos para manter a consistência.

## 🎨 Adicionando Novos Estilos

### Exemplo: Novo tipo de botão

```css
.btn-primary {
  padding: var(--spacing);
  background-color: var(--color2);
  color: var(--color1);
  border: 2px solid var(--color2);
  border-radius: var(--border-radius);
  cursor: pointer;
  transition: var(--transition);
}

.btn-primary:hover {
  background-color: var(--color4);
  border-color: var(--color4);
}
```

## 🚀 Próximos Passos Recomendados

### 1. Implementar Busca Funcional
```javascript
document.querySelector('.search-bar input').addEventListener('input', (e) => {
  const query = e.target.value.toLowerCase();
  // Filtrar projetos baseado em query
});
```

### 2. Adicionar Dark/Light Mode
Implementar toggle de tema usando `prefers-color-scheme` e JavaScript.

### 3. Integrar com Backend
- Carregar projetos de uma API
- Salvar preferências do usuário
- Sistema de autenticação

### 4. Progressive Web App
- Adicionar `manifest.json`
- Service Worker para offline
- Cache de assets

## 🔍 Testing

Para testar responsive design:
- Desktop: 1920px, 1440px
- Tablet: 768px, 1024px
- Mobile: 375px, 414px

Use `F12` → DevTools → Device Toolbar para testar.

## 📊 Performance

Checklist de otimização:
- ✅ Fontes do sistema (sem web fonts lentas)
- ✅ Imagens otimizadas (WebP)
- ✅ CSS minificado em produção
- ⏳ Lazy loading para projetos futuros
- ⏳ Compressão Gzip

## 🛡️ Acessibilidade (A11y)

Já implementado:
- ✅ Labels semânticas (`<section>`, `<aside>`, `<nav>`)
- ✅ Atributos `alt` em imagens
- ✅ `aria-label` em inputs
- ✅ Contraste de cores atende WCAG AA
- ✅ Responsividade para todos os tamanhos

Melhorias futuras:
- [ ] Adicionar modo de alto contraste
- [ ] Suporte a teclado (Tab navigation)
- [ ] Suporte a screen readers melhorado

## 📱 Mobile-First Development

O projeto é construído com mobile-first em mente:
1. Estilos base para mobile
2. Media queries adicionam estilos para telas maiores
3. Breakpoint principal: 768px

## 🐛 Debugging

Ative as DevTools do navegador (F12) para:
- Inspecionar elementos
- Debug de estilos CSS
- Console para JavaScript (quando implementado)

## 📚 Referências

- [MDN - CSS Grid](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Grid_Layout)
- [MDN - Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout)
- [MDN - Custom Properties](https://developer.mozilla.org/en-US/docs/Web/CSS/--*)
- [WCAG 2.1](https://www.w3.org/WAI/WCAG21/quickref/)

---

Divirta-se desenvolvendo! 🚀
