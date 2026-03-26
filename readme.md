# 🎉 Walter Mesas RJ - Site HTML/CSS/JavaScript

Bem-vindo ao site completo do **Walter Mesas RJ** em HTML, CSS e JavaScript puro!

## 📁 Estrutura de Arquivos

```
walter-mesas-rj-html/
├── index.html              # Página principal (HTML)
├── css/
│   └── style.css          # Estilos do site (CSS)
├── js/
│   └── script.js          # Funcionalidades (JavaScript)
├── assets/
│   ├── logo-oficial.jpg   # Logo da marca
│   ├── hero-home.png      # Imagem de fundo da home
│   └── hero-contact.jpg   # Imagem da página de contato
└── README.md              # Este arquivo
```

## 🚀 Como Usar

### 1. Abrir Localmente
Simplesmente abra o arquivo `index.html` no seu navegador:
- Clique duas vezes em `index.html`
- Ou arraste o arquivo para o navegador

### 2. Servir com um Servidor Local (Recomendado)

**Usando Python 3:**
```bash
python -m http.server 8000
```
Depois acesse: `http://localhost:8000`

**Usando Node.js (http-server):**
```bash
npm install -g http-server
http-server
```

**Usando PHP:**
```bash
php -S localhost:8000
```

## 📋 Funcionalidades Incluídas

✅ **Menu Responsivo**: Menu mobile que se adapta a qualquer tamanho de tela  
✅ **Scroll Suave**: Navegação suave entre seções  
✅ **Animações**: Efeitos visuais ao scroll  
✅ **WhatsApp Button**: Link direto para contato via WhatsApp  
✅ **Imagens Otimizadas**: Carregamento eficiente  
✅ **Design Responsivo**: Funciona em desktop, tablet e mobile  
✅ **Acessibilidade**: Semântica HTML adequada  

## 🎨 Personalizações

### Alterar Cores
Edite as variáveis CSS no início de `css/style.css`:
```css
:root {
    --primary-color: #FCD34D;      /* Amarelo */
    --secondary-color: #1F2937;    /* Cinza escuro */
    --text-color: #111827;         /* Texto */
    --white: #FFFFFF;              /* Branco */
}
```

### Adicionar Novos Produtos
No `index.html`, copie um `product-card` e altere os dados:
```html
<div class="product-card">
    <div class="product-image">
        <img src="URL_DA_IMAGEM" alt="Nome do Produto">
    </div>
    <h3>Nome do Produto</h3>
    <p>Descrição do produto</p>
    <span class="price">Sob consulta</span>
</div>
```

### Atualizar Informações de Contato
Procure pela seção `#contato` no `index.html` e atualize:
- Telefone: `(21) 96872-9939`
- E-mails: `waltersaldanhamesas@gmail.com`
- Endereço: `R. Gen. Miguel Ferreira, 178 - Taquara`
- Horários: `Seg-Sáb 07:00 às 21:30`

## 🌐 Publicar na Web

### Opção 1: Vercel (Recomendado)
1. Acesse https://vercel.com
2. Clique em "New Project"
3. Selecione "Import Git Repository" ou faça upload direto
4. Seu site estará online em minutos!

### Opção 2: Netlify
1. Acesse https://netlify.com
2. Arraste a pasta do projeto ou conecte seu repositório
3. Seu site estará publicado automaticamente

### Opção 3: GitHub Pages
1. Crie um repositório no GitHub
2. Faça upload dos arquivos
3. Ative "GitHub Pages" nas configurações
4. Seu site estará em `https://seu-usuario.github.io/seu-repositorio`

### Opção 4: Hospedagem Tradicional (FTP)
1. Compacte os arquivos em um `.zip`
2. Faça upload via FTP para o servidor
3. Configure o servidor web para servir `index.html`

## 📱 Responsividade

O site é totalmente responsivo e funciona em:
- ✅ Desktop (1920px+)
- ✅ Tablet (768px - 1024px)
- ✅ Mobile (até 480px)

## 🔧 Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilos modernos com Grid e Flexbox
- **JavaScript Vanilla**: Sem dependências externas
- **Intersection Observer API**: Animações ao scroll
- **Responsive Design**: Mobile-first approach

## 📞 Contato

Para dúvidas ou sugestões sobre o site, entre em contato:
- **Telefone**: (21) 96872-9939
- **E-mail**: waltersaldanhamesas@gmail.com
- **WhatsApp**: [Clique aqui](https://wa.me/5521968729939)

## 📄 Licença

Este site foi desenvolvido especificamente para **Walter Mesas RJ**. Todos os direitos reservados © 2026.

---

**Desenvolvido com ❤️ para Walter Mesas RJ**

Aproveite seu novo site! 🚀
