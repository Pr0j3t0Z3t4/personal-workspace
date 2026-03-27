# Personal Workspace Dashboard

Uma dashboard pessoal moderna, responsiva e visualmente atraente. Perfeita para centralizar acesso rápido aos seus principais projetos e ferramentas.

## ✨ Características

- **Design Moderno**: Interface limpa com paleta de cores sofisticada (verde musgo, azul acinzentado e preto)
- **Responsivo**: Totalmente adaptável para desktop, tablet e mobile
- **Sidebar Intuitiva**: Menu de navegação com perfil do usuário integrado
- **Barra de Busca**: Campo de pesquisa funcional no header
- **Grid Dinâmico**: Projetos exibidos em grid que se adapta ao tamanho da tela
- **Efeitos Interativos**: Animações suaves ao passar o mouse
- **Background Grid**: Padrão visual único no fundo

## 📁 Estrutura do Projeto

```
personal-workspace/
├── index.html          # Arquivo HTML principal
├── style.css           # Folha de estilos otimizada
├── normalize.css       # Normalização de estilos padrão
├── README.md           # Este arquivo
└── img/
    └── e9b5d3db99cd89c36f7db3a81ccbded8.webp  # Avatar do usuário
```

## 🎨 Paleta de Cores

| Cor | Valor | Uso |
|-----|-------|-----|
| Branco | `#ffffff` | Texto e elementos principais |
| Verde Musgo | `#a1ac88` | Destaque nos cards de projetos |
| Cinza | `#757575` | Cor secundária (reservada) |
| Azul Acinzentado | `#464d70` | Bordas e efeitos hover |
| Preto | `#000000` | Fundo principal |

## 🚀 Como Usar

1. **Clone ou download** o repositório
2. **Abra** o arquivo `index.html` em seu navegador
3. **Customize** conforme necessário:
   - Adicione novos links na seção de "Projetos"
   - Atualize o nome do usuário na sidebar
   - Troque a imagem do avatar

## 🛠️ Personalização

### Adicionar Novos Projetos

No HTML, adicione novos itens na lista dentro de `#content`:

```html
<li><a href="seu-link-aqui">Novo Projeto</a></li>
```

### Alterar Nome do Usuário

Localize na sidebar e modifique:
```html
<span class="user-name">Seu Nome</span>
```

### Trocar Avatar

Substitua a imagem em `img/` e atualize o caminho:
```html
<img src="img/sua-imagem.webp" alt="Avatar">
```

## 🎯 Tecnologias

- **HTML5** - Estrutura semântica
- **CSS3** - Layout com Grid, Flexbox e Custom Properties
- **Normalize.css** - Reset de estilos do navegador

## 📱 Responsividade

- **Desktop**: Layout com sidebar lateral e grid 4+ colunas
- **Tablet**: Sidebar reposicionada como barra horizontal
- **Mobile**: Layout stackado com sidebar acima do conteúdo

Breakpoint principal: 768px

## ✅ Otimizações Implementadas

- ✔️ Propriedades CSS consolidadas com variáveis (`:root`)
- ✔️ Fontes do sistema para melhor performance
- ✔️ `box-sizing: border-box` aplicado globalmente
- ✔️ Transições suaves com `transition` centralizada
- ✔️ Background grid fixo para efeito visual constante
- ✔️ Flexibilidade com `flex-wrap` em headers
- ✔️ Sombras e efeitos de hover aprimorados
- ✔️ Caminhos de imagem relativos (portabilidade)

## 🔧 Melhorias Futuras Sugeridas

- [ ] Adicionar interatividade com JavaScript
- [ ] Implementar busca funcional
- [ ] Integrar com APIs de projetos
- [ ] Tema escuro/claro toggle
- [ ] Animações mais avançadas
- [ ] Seção de estatísticas/widgets
- [ ] Local storage para dados do usuário
- [ ] PWA capabilities

## 📄 Licença

Uso livre e aberto para fins pessoais e educacionais.

## 👨‍💻 Autor

Desenvolvido como um workspace pessoal moderno e funcional.

---

**Última atualização**: Março de 2026  
**Status**: ✅ Completo e otimizado