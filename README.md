```markdown
# 👤 Portfólio Pessoal & Trajetória

Este repositório contém o código-fonte do meu **portfólio pessoal**, uma plataforma interativa concebida para apresentar a minha história, a minha jornada de aprendizagem, competências técnicas e projetos desenvolvidos no universo da tecnologia, música e edição multimédia.

---

## 📖 Sobre Mim & O Projeto

O objetivo principal deste site é servir como um cartão de visita digital e uma biografia viva. Nele, partilho a minha evolução, os meus projetos e as áreas em que atuo:

- **Desenvolvimento Web:** Criação de interfaces modernas, responsivas e focadas na experiência do utilizador.
- **Produção Musical:** Trabalhos de composição, arranjos instrumentais, remixes e masterização de áudio.
- **Criação Multimédia:** Edição de vídeo, tratamento de imagem e produção de conteúdos para redes sociais.

---

## 🚀 Funcionalidades do Site

- 🌓 **Modo Escuro & Claro (Dark/Light Mode):** Alternância simples de tema visual com gravação da preferência no `localStorage`.
- 📱 **Design Responsivo:** Navegação adaptada a dispositivos móveis (menu hambúrguer) e monitores desktop.
- 🎨 **Estética Glassmorphism:** Efeitos visuais modernos com desfoques, cartões dinâmicos e sombras personalizadas.
- 🎧 **Ícones Temáticos Personalizados:** Utilização do Font Awesome para representar competências específicas (Composição, Remix, Masterização, Edição de Vídeo, etc.).
- ✉️ **Formulário de Contacto:** Secção dedicada para mensagens diretas e pedidos de colaboração.

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Estruturação semântica e acessível.
- **CSS3:** Variáveis de estilo, Flexbox, CSS Grid e animações suaves.
- **JavaScript (ES6+):** Lógica de navegação, troca de temas e interação com o DOM.
- **Font Awesome 6:** Iconografia vetorial para marcas e ferramentas técnicas.

---

## 📂 Estrutura de Ficheiros

```text
├── index.html        # Estrutura principal com a biografia, projetos e contacto
├── style.css         # Estilos globais, temas (claro/escuro) e responsividade
├── script.js        # Lógica de alternância de tema e controlo do menu
├── .env.example      # Exemplo de variáveis de ambiente
├── .gitignore        # Ficheiros ignorados no repositório Git
└── README.md         # Documentação sobre o portfólio

```

---

## 💻 Como Executar Localmente

1. **Clonar o repositório:**
```bash
git clone [https://github.com/seu-usuario/seu-repositorio.git](https://github.com/seu-usuario/seu-repositorio.git)

```


2. **Entrar na pasta do projeto:**
```bash
cd seu-repositorio

```


3. **Abrir o projeto:**
* Dê um duplo clique no ficheiro `index.html` para abrir diretamente no navegador.
* **Ou** no VS Code, utilize a extensão **Live Server** (clique com o botão direito no `index.html` e escolha *"Open with Live Server"*).



---

## ⚙️ Variáveis de Ambiente

Para manter dados sensíveis (como chaves de APIs de e-mail ou serviços externos) protegidos, configure o ficheiro `.env` com base no `.env.example`:

```env
SITE_URL=http://localhost:3000
EMAIL_SERVICE_ID=seu_service_id
EMAIL_TEMPLATE_ID=seu_template_id
EMAIL_PUBLIC_KEY=sua_chave_publica

```