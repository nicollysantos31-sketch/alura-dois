# 📈 Mercado Financeiro - Dashboard Interativo

Um website moderno e otimizado sobre mercado financeiro, desenvolvido com **HTML5**, **CSS3**, **JavaScript** e **p5.js** para visualizações de dados em tempo real.

## 🎯 Características

- ✅ **Layout Responsivo** - Adaptado para dispositivos móveis e desktop
- ✅ **Visualização Interativa** - Gráficos em tempo real com p5.js
- ✅ **Design Otimizado** - CSS com variáveis e performance otimizada
- ✅ **Navegação Suave** - Scroll automático entre seções
- ✅ **Dados Financeiros** - Tabelas com cotações atualizadas
- ✅ **Formulário de Contato** - Sistema validado e funcional
- ✅ **Performance** - Código minimalista e sem dependências externas desnecessárias

## 📁 Estrutura de Arquivos

```
mercado-financeiro/
├── index.html          # Estrutura HTML principal
├── style.css           # Estilos otimizados com variáveis CSS
├── script.js           # Lógica JavaScript e p5.js
└── README.md          # Este arquivo
```

## 🚀 Como Usar

### 1. Clone o Repositório
```bash
git clone https://github.com/nicollysantos31-sketch/alura-dois.git
cd alura-dois
```

### 2. Abra no Navegador
Abra o arquivo `index.html` diretamente no seu navegador:
```bash
open index.html
# ou
start index.html  # Windows
xdg-open index.html  # Linux
```

### 3. Ou use um Servidor Local
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server

# Acesse: http://localhost:8000
```

## 📊 Seções do Dashboard

### 1. **Início**
- Bem-vindo ao dashboard
- Informações sobre cotações, análise e performance
- Cards informativos com hover effect

### 2. **Dados**
- Tabela com índices financeiros
- IBOVESPA, Dólar, Ouro e Bitcoin
- Indicadores de preço e variação

### 3. **Gráfico**
- Visualização em tempo real com p5.js
- Controles: Iniciar, Parar, Resetar
- Exibição de valores máximo, mínimo e média

### 4. **Contato**
- Formulário de contato validado
- Validação de email
- Feedback de sucesso/erro

## 🎨 Paleta de Cores

```css
--color-primary: #2563eb (Azul)
--color-secondary: #1e40af (Azul Escuro)
--color-success: #10b981 (Verde)
--color-danger: #ef4444 (Vermelho)
--color-warning: #f59e0b (Amarelo)
--color-dark: #1f2937 (Cinza Escuro)
--color-light: #f3f4f6 (Cinza Claro)
```

## ⚙️ Configurações do p5.js

```javascript
CONFIG = {
    CANVAS_WIDTH: 800,
    CANVAS_HEIGHT: 400,
    FPS: 60,
    NUM_POINTS: 120,
    ANIMATION_SPEED: 0.02
}
```

Você pode ajustar essas configurações no arquivo `script.js`.

## 🔧 Funcionalidades Principais

### Animação de Gráfico
- Inicia com o botão "Iniciar"
- Pausa com "Parar"
- Reseta com "Resetar"
- Mostra valores em tempo real

### Navegação Ativa
- Links de navegação destacam seção atual
- Scroll automático suave
- Atualização dinâmica ao rolar página

### Validação de Formulário
- Validação de campos vazios
- Validação de formato de email
- Mensagens de feedback ao usuário

### Responsividade
- Breakpoint em 768px para tablets/móveis
- Grid adaptativo
- Imagens e canvas redimensionáveis

## 🌐 Compatibilidade

- ✅ Chrome (últimas versões)
- ✅ Firefox (últimas versões)
- ✅ Safari (últimas versões)
- ✅ Edge (últimas versões)
- ✅ Mobile browsers (iOS Safari, Chrome Android)

## 📦 Dependências

- **p5.js** (CDN) - Biblioteca para visualização
- Sem dependências de CSS/JS frameworks pesados!

## 🎓 Conceitos Técnicos Utilizados

### HTML5
- Semantic HTML
- Meta tags de responsividade
- Acessibilidade básica

### CSS3
- CSS Grid e Flexbox
- Custom Properties (Variáveis CSS)
- Media Queries
- Animações e Transições
- Gradientes

### JavaScript
- Seleção e manipulação do DOM
- Event Listeners
- Debounce e Throttle
- Validação de formulários

### p5.js
- Setup e Draw
- Rendering 2D
- Interação com usuário
- Canvas responsivo

## 💡 Dicas de Otimização

1. **Performance**: Redimensione o canvas conforme necessário
2. **Mobile**: Teste com Chrome DevTools Device Mode
3. **Acessibilidade**: Adicione mais `aria-labels` se necessário
4. **SEO**: Personalize as meta tags no `index.html`

## 🔒 Segurança

- Validação de entrada de usuário
- Proteção contra XSS com textContent
- CORS configurado para APIs futuras

## 📝 Licença

MIT License - Livre para uso pessoal e comercial

## 👨‍💻 Autor

**Nicolly Santos**
- GitHub: [@nicollysantos31-sketch](https://github.com/nicollysantos31-sketch)
- Projeto: Dashboard de Mercado Financeiro

## 🤝 Contribuições

Contribuições são bem-vindas! Sinta-se livre para:
- Abrir issues com sugestões
- Fazer fork e criar pull requests
- Compartilhar ideias de melhorias

## 🐛 Reportar Bugs

Se encontrar um bug, crie uma issue no repositório com:
- Descrição do problema
- Passos para reproduzir
- Navegador e versão
- Screenshots se aplicável

## 📚 Recursos Úteis

- [p5.js Documentation](https://p5js.org/reference/)
- [MDN Web Docs](https://developer.mozilla.org/)
- [CSS Tricks](https://css-tricks.com/)
- [JavaScript.info](https://javascript.info/)

## 🎉 Agradecimentos

Desenvolvido com ❤️ para a comunidade Alura

---

**Última atualização**: 19 de junho de 2026
**Versão**: 1.0.0
