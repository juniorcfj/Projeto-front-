🛍️ Loja Drip

Aplicação front-end de uma loja virtual desenvolvida com React + Vite, com foco em performance, componentização e experiência do usuário.

📌 Sobre o Projeto

O Loja Drip é uma interface de e-commerce que permite visualizar produtos, navegar entre páginas, visualizar detalhes e simular interações como carrinho de compras.

O projeto foi estruturado utilizando boas práticas de desenvolvimento front-end, incluindo:

Componentização com React
Gerenciamento de rotas com React Router
Consumo de API com Axios
Estilização moderna com Tailwind CSS
🚀 Tecnologias Utilizadas
React 19
Vite
React Router DOM
Axios
Tailwind CSS
React Icons
ESLint

Estrutura do projeto

src/
│
├── components/
│   ├── AbaProdutos/
│   ├── HomePage/
│   ├── header.jsx
│   ├── footer.jsx
│   ├── cartIcon.jsx
│   ├── cartDropDown.jsx
│   ├── productInfo.jsx
│   ├── relatedProducts.jsx
│   └── ...
│
├── App.jsx
├── main.jsx
└── services/


Principais Componentes
Header / Footer → Layout global
Hero → Destaque inicial da página
ProductListing / ProductCard → Listagem de produtos
ProductInfo → Detalhes do produto
Cart (Icon + Dropdown) → Carrinho de compras
FilterGroup → Filtros de produtos
Gallery / ImageGallery → Visualização de imagens

⚙️ Como Executar o Projeto

1. Clone o repositório
git clone <URL_DO_REPOSITORIO>
2. Acesse a pasta
cd loja-drip
3. Instale as dependências
npm install
4. Rode o projeto
npm run dev

O projeto estará disponível em:

http://localhost:5173
📦 Scripts Disponíveis
npm run dev       # Inicia o servidor de desenvolvimento
npm run build     # Gera build de produção
npm run preview   # Visualiza o build
npm run lint      # Verifica padrões de código
🌐 Funcionalidades


✅ Listagem de produtos
✅ Visualização detalhada de produtos
✅ Carrinho de compras (UI)
✅ Navegação entre páginas
✅ Filtros de produtos
✅ Layout responsivo
🔌 Integração com API

O projeto utiliza o Axios para consumir APIs externas (ex: produtos).
Caso necessário, configure a base da API em:

src/services/api.js
🎨 Estilização

A aplicação utiliza Tailwind CSS, permitindo:

Design responsivo
Estilização rápida e consistente
Componentes reutilizáveis
📈 Melhorias Futuras
Integração completa com backend
Autenticação de usuários
Persistência do carrinho
Sistema de pagamentos
Dashboard administrativo
👨‍💻 Autor

Desenvolvido por José Júnior