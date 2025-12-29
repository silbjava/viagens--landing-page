# 🌍 Landing Page - Viagens dos Sonhos

Projeto de uma landing page simples e responsiva para uma agência de viagens, desenvolvido com HTML e CSS puro.

## 📋 Sobre o Projeto

Este é um projeto de landing page criado para praticar os fundamentos de HTML5 e CSS3. A página apresenta destinos turísticos incríveis ao redor do mundo e inclui um formulário de contato para os visitantes interessados.

### ✨ Funcionalidades

- **Banner Hero**: Imagem de destaque com texto sobreposto
- **Navegação Interna**: Menu fixo que navega entre as seções da página
- **Cards de Destinos**: Apresentação visual de destinos turísticos
- **Seção Sobre**: Informações sobre a agência
- **Formulário de Contato**: Para captação de leads
- **Botões de Navegação**: Links para voltar ao topo da página

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica da página
- **CSS3**: Estilização e layout responsivo

## 📂 Estrutura de Arquivos

```
projeto-landing-page/
│
├── index.html          # Arquivo HTML principal
├── style.css           # Arquivo de estilos CSS
└── README.md           # Documentação do projeto
```

## 🚀 Como Executar o Projeto

### Opção 1: Abrir Diretamente no Navegador

1. **Baixe ou clone o projeto** para o seu computador
2. **Crie uma pasta** para o projeto (ex: `landing-page-viagens`)
3. **Crie os arquivos necessários**:
   - `index.html` - Cole o código HTML
   - `style.css` - Cole o código CSS
4. **Abra o arquivo `index.html`** no seu navegador preferido:
   - Clique duas vezes no arquivo, ou
   - Clique com botão direito → "Abrir com" → Escolha seu navegador

### Opção 2: Usando um Editor de Código (Recomendado)

1. **Instale um editor de código** (ex: [VS Code](https://code.visualstudio.com/))
2. **Abra a pasta do projeto** no editor
3. **Instale a extensão "Live Server"** (VS Code):
   - Vá em Extensions (Ctrl+Shift+X)
   - Pesquise por "Live Server"
   - Clique em Install
4. **Clique com botão direito** no arquivo `index.html`
5. **Selecione "Open with Live Server"**
6. A página abrirá automaticamente no navegador!

### Opção 3: Usando Python (se você tem Python instalado)

1. Abra o terminal na pasta do projeto
2. Execute um dos comandos abaixo:

```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

3. Acesse `http://localhost:8000` no navegador

## 📱 Requisitos do Projeto

Este projeto foi desenvolvido seguindo os seguintes requisitos:

### ✅ Requisitos Mínimos Atendidos

1. **Banner dentro do `<main>`**
   - ✓ Banner com imagem de fundo
   - ✓ Texto overlay (h1 e p)
   - ✓ Call-to-action button

2. **Navegação `<nav>`**
   - ✓ Menu de navegação fixo no topo
   - ✓ Links internos para as seções
   - ✓ Efeito hover nos links

3. **Navegação para o topo**
   - ✓ Botões "Voltar ao Início" em cada seção
   - ✓ Botão no footer para voltar ao topo
   - ✓ Todas navegações acontecem na mesma aba

### 🎨 Especificações Técnicas

- **Tags Semânticas**: `<nav>`, `<main>`, `<section>`, `<footer>`
- **IDs para Navegação**: #home, #destinos, #sobre, #contato
- **Classes Reutilizáveis**: .card, .botao, .voltar-topo
- **Efeitos Hover**: Mudança de cor em links e botões
- **Acessibilidade**: Atributos `alt` em todas as imagens

## 🎯 Seções da Página

### 1. Home (Banner)
- Imagem de fundo inspiradora
- Título principal e subtítulo
- Botão para ver destinos

### 2. Destinos
- Grid de cards com 3 destinos
- Cada card contém: imagem, título, descrição e botão
- Efeito hover nos cards

### 3. Sobre
- Informações sobre a agência
- Texto descritivo em parágrafos

### 4. Contato
- Formulário com campos:
  - Nome (obrigatório)
  - E-mail (obrigatório)
  - Telefone (opcional)
  - Mensagem (obrigatório)
- Botão de envio

## 🎨 Paleta de Cores

- **Primária**: #4CAF50 (Verde)
- **Secundária**: #2196F3 (Azul)
- **Texto Escuro**: #333
- **Texto Claro**: #666
- **Background**: #f4f4f4
- **Hover**: #555

## 📖 Conceitos Aprendidos

- Estrutura HTML semântica
- Separação de arquivos (HTML e CSS)
- Navegação interna com âncoras (#)
- Flexbox para layout
- Efeitos hover com CSS
- Formulários HTML
- Posicionamento fixo (fixed)
- Box model e espaçamentos

## 🔧 Possíveis Melhorias Futuras

- [ ] Adicionar JavaScript para validação de formulário
- [ ] Tornar o menu responsivo para mobile (hamburguer)
- [ ] Adicionar mais animações CSS
- [ ] Implementar scroll suave (smooth scroll)
- [ ] Adicionar mais destinos turísticos
- [ ] Criar um slider de imagens no banner
- [ ] Integrar com backend para envio real de formulário

## 📝 Observações

- As imagens utilizadas são da plataforma **Unsplash** (banco de imagens gratuito)
- O formulário é apenas visual (não envia dados para nenhum servidor)
- O projeto é totalmente responsivo e funciona em diferentes tamanhos de tela

## 👨‍💻 Autor

Projeto desenvolvido como parte dos estudos de Desenvolvimento Web Frontend.

## 📄 Licença

Este projeto é de código aberto e está disponível para uso educacional.

---

⭐ Se gostou do projeto, deixe uma estrela!

📧 Dúvidas? Entre em contato através do formulário da página!