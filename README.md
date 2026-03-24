# TecBlog Modernization

Uma aplicação estática de blog de tecnologia, refatorada com **TailwindCSS** para uma estética "Deep Dark Tech" premium, utilizando design patterns avançados como Glassmorphism, grid layouts dinâmicos e tipografia imersiva.

## 🚀 Sobre a Refatoração
O projeto original era um website básico HTML/CSS focado em layout fixo. Ele foi totalmente modernizado para se adequar como uma peça de portfólio de alta fidelidade visual e reponsividade móvel completa.

### Stack Tecnológico
- **HTML5 Semântico:** Estrutura otimizada para SEO e acessibilidade.
- **TailwindCSS:** Utilizado extensivamente para o design responsivo, incluindo variáveis de cor personalizadas, theming e container queries.
- **Google Fonts:** Tipografias `Plus Jakarta Sans` (para títulos limpos e modernos) e `Inter` (para parágrafos de alta legibilidade).
- **Google Material Symbols:** Para a iconografia premium no novo design de UI.

## 📸 Screenshots do Novo Design

### 🏠 Home Page
![Home Page](docs/home.png)

### 📰 Conteúdo do Artigo
![Article Page](docs/article.png)

### 🗂️ Categorias
![Categories Page](docs/categories.png)

### ℹ️ Sobre Nós
![About Page](docs/about.png)

## 🛠️ Como rodar localmente
Não há comandos complexos de build (Node.js/npm) necessários, pois o Tailwind é injetado via CDN com um script de configuração dedicado no `<head>`.

1. Clone este repositório.
2. Abra `index.html` em seu navegador web para visualizar o website completo. Opcionalmente, para garantir que as rotas e assets carreguem sem bloqueios de CORS locais (embora seja puramente estático), você pode rodar o server embutido do Python ou a extensão Live Server do VS Code:
   ```bash
   python -m http.server 8080
   ```
   E acessar `http://localhost:8080` no seu browser.
