# Drabyanca Odontologia - Website & Blog

Site oficial da Dra. Byanca do Prado, especialista em Endodontia (Canal) em Itajubá - MG.

## 🌐 Acesso ao Site

- **Site Principal:** [https://urbiatec.github.io/drabyanca/](https://urbiatec.github.io/drabyanca/)
- **Blog:** [https://urbiatec.github.io/drabyanca/blog/](https://urbiatec.github.io/drabyanca/blog/)

## 📁 Estrutura do Repositório

```
drabyanca/
├── index.html              # Página principal do site
├── robots.txt              # Configurações para bots de busca
├── sitemap.xml             # Mapa do site para SEO
├── assets/                 # Imagens e recursos do site
│   ├── *.jpg              # Fotos do consultório e equipe
│   └── *.png              # Logos e ícones
└── blog/                   # Estrutura completa do blog
    ├── index.md           # Página principal do blog
    ├── README.md          # Instruções específicas do blog
    ├── blog-style.css     # Estilos CSS para o blog
    ├── posts/             # Artigos e posts do blog
    │   └── *.md          # Posts em formato Markdown
    └── categorias/        # Categorias organizadas por tema
        └── *.md          # Páginas de categorias
```

## 🚀 Como Executar Localmente

### Opção 1: Servidor HTTP Simples
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (se tiver npx instalado)
npx serve .

# Com PHP
php -S localhost:8000
```

### Opção 2: GitHub Pages (Recomendado)
O site está configurado para funcionar automaticamente com GitHub Pages. Qualquer commit na branch `main` será automaticamente publicado.

## 📝 Como Adicionar Conteúdo ao Blog

### Adicionando um Novo Post

1. Crie um arquivo `.md` na pasta `blog/posts/` com o formato: `YYYY-MM-DD-titulo-do-post.md`
2. Use a estrutura padrão:

```markdown
# Título do Post

**Data:** DD de Mês de YYYY  
**Autor:** Equipe Drabyanca  
**Categoria:** [Categoria](../categorias/categoria.md)

Conteúdo do post aqui...

[Voltar para o Blog](../index.md)
```

3. Adicione o link do novo post em `blog/index.md` na seção "Últimos Posts"

### Adicionando uma Nova Categoria

1. Crie um arquivo `.md` na pasta `blog/categorias/` com o nome da categoria
2. Use a estrutura padrão:

```markdown
# Categoria: Nome da Categoria

Descrição da categoria...

## Posts

- [Nome do Post](../posts/nome-do-post.md)

[Voltar para o Blog](../index.md)
```

3. Adicione o link da nova categoria em `blog/index.md` na seção "Categorias"

## 🎨 Personalização

### Cores e Estilos
- **Site Principal:** Estilos inline no `index.html`
- **Blog:** `blog/blog-style.css`
- **Paleta de Cores:** Tons rosé e marfim para transmitir delicadeza e profissionalismo

### Imagens
- Adicione novas imagens na pasta `assets/`
- Use formatos otimizados (JPG para fotos, PNG para logos)
- Mantenha nomes descritivos para facilitar manutenção

## 📱 Recursos do Site

### Site Principal (`index.html`)
- ✅ Design responsivo
- ✅ Seções: Início, Sintomas, Serviços, Diferenciais, Galeria, FAQ, Localização
- ✅ Integração com WhatsApp
- ✅ Galeria de fotos com lightbox
- ✅ Localização com Google Maps
- ✅ Schema.org para SEO
- ✅ Meta tags otimizadas

### Blog (`blog/`)
- ✅ Estrutura organizada em posts e categorias
- ✅ Navegação intuitiva
- ✅ Markdown para fácil edição
- ✅ Links internos otimizados
- ✅ Compatível com GitHub Pages

## 🔧 Tecnologias Utilizadas

- **HTML5:** Estrutura semântica
- **CSS3:** Estilos modernos e responsivos
- **JavaScript:** Interatividade e funcionalidades
- **Markdown:** Conteúdo do blog
- **GitHub Pages:** Hospedagem gratuita

## 📞 Contato

- **Dra. Byanca do Prado**
- **WhatsApp:** (35) 9 9868-6030
- **Telefone:** (35) 3622-1287
- **Endereço:** Rua Maestro Luiz Ramos de Lima, 73 - Itajubá/MG

## 📋 Instruções de Manutenção

1. **Atualizações de Conteúdo:** Edite diretamente os arquivos `.md` no blog
2. **Novas Funcionalidades:** Modifique `index.html` conforme necessário
3. **Imagens:** Adicione na pasta `assets/` e referencie corretamente
4. **SEO:** Mantenha `robots.txt` e `sitemap.xml` atualizados
5. **Backup:** O Git já serve como sistema de backup automático

---

**Desenvolvido com ❤️ para a Drabyanca Odontologia**