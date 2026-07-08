# 🚀 Syntaxware - Tênis e Sneakers Online

Uma loja de e-commerce moderna e responsiva especializada em tênis e sneakers, construída com HTML5, CSS3 e design modular.

## 📋 Sobre o Projeto

**Syntaxware** é uma plataforma de vendas online focada em oferecer os melhores tênis e sneakers para homens e mulheres. O projeto apresenta um design contemporâneo e minimalista com foco em usabilidade e experiência do usuário.

### Objetivo
Fornecer uma experiência de compra online intuitiva e agradável com uma vasta variedade de estilos de calçados, mantendo qualidade, conforto e presença visual forte.

## 📁 Estrutura do Projeto

```
ecommerce-syntaxware/
├── index.html                 # Página principal
├── README.md                  # Documentação
├── css/
│   ├── reset.css             # Reset de estilos padrão do navegador
│   ├── variables.css         # Variáveis e fontes globais
│   ├── base.css              # Estilos base (botões, tipografia, etc)
│   ├── components/
│   │   ├── header.css        # Estilos do cabeçalho e navegação
│   │   ├── hero.css          # Seção hero/banner principal
│   │   ├── product-category.css # Cards de categorias de produtos
│   │   ├── product-grid.css  # Grid de produtos em destaque
│   │   └── footer.css        # Estilos do rodapé
│   └── layout.css            # Estilos de layout e grid (referenciado)
├── images/
│   ├── logo/                 # Logo da marca
│   ├── icons/                # Ícones (menu, usuário, ajuda, carrinho, redes sociais)
│   ├── banners/              # Imagens de banners e hero
│   └── products/             # Imagens dos produtos
└── .git/                      # Controle de versão Git
```

## 🎨 Design e Componentes

### Seções Principais

1. **Header (Cabeçalho)**
   - Logo interativa
   - Menu de navegação responsivo (hamburger em mobile)
   - Categorias principais: Masculino, Feminino, Outlet
   - Menu superior com links: Nossas lojas, Sobre
   - Ícones de ação: Minha Conta, Ajuda, Carrinho

2. **Hero Section**
   - Banner destaque do produto Krypto One
   - Título principal: "Transforme qualquer passo em presença."
   - Botões de ação: "Ver modelos" e "Comprar"

3. **Categorias de Produtos**
   - Casual
   - Esporte
   - Moderno
   - Futurista
   - Cada categoria com overlay e botão de navegação

4. **Grid de Produtos**
   - Card destaque com informações do Krypto One
   - Cards de produtos coloridos:
     - Sneaker Purple
     - Model
     - Sneaker Color
     - Sneaker White
     - Sneaker Silver

5. **Footer**
   - Newsletter: Inscrição por e-mail
   - Redes Sociais: Instagram, WhatsApp, TikTok, Facebook
   - Navegação completa:
     - Categoria Masculino (Casual, Esporte, Moderno, Futurista)
     - Categoria Feminino (Casual, Esporte, Moderno, Futurista)
     - Outlet (Masculino, Feminino)
     - Nossas Lojas
     - Sobre (Quem Somos, Missão)
   - Copyright

## 🎯 Características Principais

✨ **Design Moderno e Limpo**
- Arquitetura CSS modular com separação de componentes
- Variáveis CSS para consistência visual
- Design responsivo (mobile-first)

📱 **Responsividade**
- Menu hambúrguer para dispositivos móveis
- Layout adaptável para diferentes tamanhos de tela
- Breakpoint em 1280px para adjustments

🎨 **Sistema de Design**
- Tipografia unificada com Google Fonts (Ubuntu, Fira Sans, Lato)
- Cores consistentes através de variáveis CSS
- Botões com estilos definidos (outline e filled)

♿ **Acessibilidade**
- Atributos `aria-label` para ícones
- Atributos `alt` em imagens
- HTML semântico (header, nav, main, footer, section)
- Estrutura de navegação bem organizada

🔗 **Estrutura SEO-Friendly**
- Meta tags de descrição
- Title significativo
- Usando HTML5 semântico

## 🎨 Paleta de Cores e Tipografia

### Fontes
- **Fonte Principal**: Ubuntu
- **Fontes Adicionais**: Fira Sans, Lato, Merriweather (importadas do Google Fonts)

### Estilos de Botões
- **btn-outline**: Botão com borda (estilo transparent)
- **btn-filled**: Botão preenchido com cor
- Transição suave na mudança de estado

## 🚀 Como Usar

### Abrir Localmente
1. Clone o repositório
   ```bash
   git clone https://github.com/feerlobo/ecommerce-syntaxware.git
   cd ecommerce-syntaxware
   ```

2. Abra o arquivo `index.html` em seu navegador
   - Clique duplo no arquivo ou
   - Utilize um servidor local (veja abaixo)

### Usar com Servidor Local (Recomendado)

**Com Python 3:**
```bash
python -m http.server 8000
```

**Com Node.js (http-server):**
```bash
npx http-server
```

**Com Live Server (VS Code):**
- Instale a extensão "Live Server"
- Clique com botão direito no `index.html` e selecione "Open with Live Server"

Acesse `http://localhost:8000` ou `http://127.0.0.1:5500`

## 📝 Modificações e Customização

### Adicionar Novas Categorias
1. Adicione um novo `div` com classe `category-card` na seção `categories-section`
2. Atualize o CSS em `css/components/product-category.css` com background-image

### Adicionar Novos Produtos
1. Adicione um novo `div` com classe `card` na seção `grid-section`
2. Estilize em `css/components/product-grid.css`

### Customizar Cores
1. Edite as variáveis em `css/variables.css`
2. As cores se propagarão automaticamente

### Adicionar Funcionalidades JavaScript
1. Crie um arquivo `js/main.js`
2. Adicione a tag `<script>` no final do `index.html` antes de `</body>`

## 🔮 Próximos Passos (Sugestões)

- [ ] Implementar JavaScript para interatividade (carrinho, filtros, etc)
- [ ] Conectar a um backend (API REST)
- [ ] Implementar sistema de autenticação
- [ ] Criar páginas de detalhe de produto
- [ ] Implementar carrinho de compras
- [ ] Integrar sistema de pagamento
- [ ] Adicionar funcionalidade de busca e filtros
- [ ] Implementar análise (Google Analytics)
- [ ] Otimizar imagens e performance
- [ ] Criar versão PWA (Progressive Web App)

## 🛠️ Tecnologias Utilizadas

- **HTML5** - Estrutura semântica
- **CSS3** - Estilização com variáveis e responsive design
- **Fonts** - Google Fonts (Ubuntu, Fira Sans, Lato, Merriweather)
- **Git** - Controle de versão

## 📧 Contato e Informações

- **Site**: Syntaxware - Tênis e Sneakers Online
- **Descrição**: Encontre os melhores tênis e sneakers online. Ampla variedade de estilos para homens e mulheres, com qualidade e conforto garantidos.

### Redes Sociais
- Instagram
- WhatsApp
- TikTok
- Facebook

## 📄 Licença

Copyright. All Rights Reserved.

---

**Desenvolvido com ❤️ por Syntaxware**

*Transforme qualquer passo em presença.*
