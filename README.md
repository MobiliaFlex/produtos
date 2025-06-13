# Mobília Flex - Site Profissional de Puffs

Um site moderno e profissional para venda de puffs, desenvolvido com React e otimizado para performance, SEO e experiência do usuário.

## 🚀 Características Principais

- **Design Moderno**: Interface profissional e responsiva
- **Funcionalidades Avançadas**: Filtros, busca, modal de produtos com zoom
- **SEO Otimizado**: Meta tags, dados estruturados e sitemap
- **Performance**: Lazy loading, PWA e otimizações de carregamento
- **Integração WhatsApp**: Contato direto para vendas
- **Responsivo**: Funciona perfeitamente em todos os dispositivos

## 🛠️ Tecnologias Utilizadas

- **React 18** - Framework principal
- **Vite** - Build tool e servidor de desenvolvimento
- **Tailwind CSS** - Framework CSS utilitário
- **Framer Motion** - Animações suaves
- **Lucide React** - Ícones modernos
- **React Router** - Navegação entre páginas
- **React Helmet** - Gerenciamento de metadados

## 📦 Instalação

### Pré-requisitos

- Node.js 18+ 
- npm ou pnpm

### Passos para instalação

1. **Clone o repositório**
```bash
git clone <url-do-repositorio>
cd puffs-site
```

2. **Instale as dependências**
```bash
npm install
# ou
pnpm install
```

3. **Inicie o servidor de desenvolvimento**
```bash
npm run dev
# ou
pnpm run dev
```

4. **Acesse o site**
Abra [http://localhost:5173](http://localhost:5173) no seu navegador

## 🏗️ Build para Produção

```bash
npm run build
# ou
pnpm run build
```

Os arquivos otimizados serão gerados na pasta `dist/`.

## 📁 Estrutura do Projeto

```
puffs-site/
├── public/                 # Arquivos estáticos
│   ├── robots.txt         # Configuração para crawlers
│   ├── sitemap.xml        # Mapa do site
│   └── manifest.json      # Configuração PWA
├── src/
│   ├── components/        # Componentes React
│   │   ├── Navbar.jsx     # Barra de navegação
│   │   ├── HeroSection.jsx # Seção principal
│   │   ├── ProductCard.jsx # Card de produto
│   │   ├── ProductFilter.jsx # Filtros de produto
│   │   ├── ProductModal.jsx # Modal de detalhes
│   │   ├── FeaturesSection.jsx # Seção de recursos
│   │   ├── TestimonialsSection.jsx # Depoimentos
│   │   ├── CTASection.jsx # Call-to-action
│   │   ├── FAQ.jsx        # Perguntas frequentes
│   │   ├── Footer.jsx     # Rodapé
│   │   ├── SEO.jsx        # Componente SEO
│   │   └── LazyImage.jsx  # Imagem com lazy loading
│   ├── data/
│   │   └── products.json  # Dados dos produtos
│   ├── assets/
│   │   └── images/        # Imagens do site
│   ├── App.jsx           # Componente principal
│   ├── App.css           # Estilos globais
│   └── main.jsx          # Ponto de entrada
├── index.html            # Template HTML
└── package.json          # Dependências e scripts
```

## 🎨 Componentes Principais

### ProductCard
Card de produto com hover effects, badges e integração WhatsApp.

### ProductFilter
Sistema de filtros com busca por texto, categoria, preço e ordenação.

### ProductModal
Modal de visualização detalhada com zoom nas imagens e especificações completas.

### SEO
Componente para gerenciamento dinâmico de metadados e dados estruturados.

### LazyImage
Componente de imagem com carregamento sob demanda para melhor performance.

## 🔧 Configuração

### Dados dos Produtos
Os produtos são configurados no arquivo `src/data/products.json`. Estrutura:

```json
{
  "id": 1,
  "name": "Nome do Produto",
  "description": "Descrição do produto",
  "price": 299.90,
  "image": "/caminho/para/imagem.jpg",
  "dimensions": "190cm x 60cm",
  "rating": 4.5,
  "reviewCount": 15,
  "badge": "Mais Vendido"
}
```

### Contato WhatsApp
Para alterar o número do WhatsApp, edite a variável `phoneNumber` nos componentes:
- `ProductCard.jsx`
- `ProductModal.jsx`
- `CTASection.jsx`

### SEO e Metadados
Configure os metadados no arquivo `index.html` e no componente `SEO.jsx`.

## 📱 PWA (Progressive Web App)

O site está configurado como PWA com:
- Manifest.json para instalação
- Ícones otimizados
- Tema personalizado
- Shortcuts para funcionalidades principais

## 🔍 SEO

### Recursos Implementados
- Meta tags completas
- Open Graph para redes sociais
- Twitter Cards
- Dados estruturados (Schema.org)
- Sitemap XML
- Robots.txt
- URLs canônicas

### Dados Estruturados
O site inclui markup estruturado para:
- Organização/Empresa
- Produtos individuais
- Avaliações e ratings
- Informações de contato

## 📊 Performance

### Otimizações Implementadas
- Lazy loading de imagens
- Preconnect para recursos externos
- DNS prefetch para WhatsApp
- Preload de recursos críticos
- Componentes otimizados
- Bundle splitting automático

## 🎯 Funcionalidades

### Filtros de Produtos
- Busca por texto
- Filtro por categoria
- Filtro por faixa de preço
- Ordenação múltipla
- Resultados em tempo real

### Modal de Produtos
- Visualização detalhada
- Zoom interativo nas imagens
- Especificações técnicas
- Integração WhatsApp
- Seleção de quantidade

### Integração WhatsApp
- Botões estratégicos
- Mensagens pré-formatadas
- Informações do produto incluídas
- Múltiplos pontos de contato

## 🚀 Deploy

### Netlify
1. Faça build do projeto: `npm run build`
2. Faça upload da pasta `dist/` para o Netlify
3. Configure redirects se necessário

### Vercel
1. Conecte o repositório ao Vercel
2. Configure o comando de build: `npm run build`
3. Configure a pasta de output: `dist`

### Servidor Próprio
1. Faça build do projeto: `npm run build`
2. Copie os arquivos da pasta `dist/` para o servidor
3. Configure o servidor web para servir arquivos estáticos

## 🔧 Manutenção

### Atualizando Produtos
1. Edite o arquivo `src/data/products.json`
2. Adicione as imagens na pasta `src/assets/images/`
3. Faça rebuild do projeto

### Atualizando Conteúdo
- **Depoimentos**: Edite o componente `TestimonialsSection.jsx`
- **FAQ**: Edite o componente `FAQ.jsx`
- **Informações da empresa**: Edite o componente `Footer.jsx`

## 📞 Suporte

Para dúvidas ou suporte técnico, entre em contato através do WhatsApp configurado no site ou através dos canais de contato da Mobília Flex.

## 📄 Licença

Este projeto foi desenvolvido especificamente para a Mobília Flex. Todos os direitos reservados.

---

**Desenvolvido com ❤️ por Manus AI**

