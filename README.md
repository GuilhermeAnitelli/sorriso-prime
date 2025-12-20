# Sorriso Prime 🦷

Landing page moderna e responsiva para clínica odontológica especializada em implantes, estética dental e ortodontia.

## 📋 Sobre o Projeto

O Sorriso Prime é um site institucional desenvolvido para clínicas odontológicas que desejam destacar seus serviços e facilitar o agendamento de consultas. Com design limpo e profissional, o site foi criado para converter visitantes em pacientes.

## ✨ Funcionalidades

- **Hero Section**: Apresentação impactante com call-to-action para agendamento
- **Serviços**: Destaque para os principais tratamentos oferecidos
  - Implantes dentários
  - Clareamento dental a laser
  - Ortodontia invisível
- **Formulário de Contato**: Sistema de agendamento integrado via Formspree
- **Design Responsivo**: Adaptável a diferentes dispositivos e tamanhos de tela
- **SEO Otimizado**: Meta tags configuradas para redes sociais (Open Graph e Twitter Cards)
- **Ícones Modernos**: Utilização da biblioteca Phosphor Icons

## 🛠️ Tecnologias Utilizadas

- **HTML5**: Estrutura semântica
- **CSS3**: Estilização e layout responsivo
- **Google Fonts**: Tipografias Open Sans e Playfair Display
- **Phosphor Icons**: Biblioteca de ícones moderna
- **Formspree**: Serviço para processamento de formulários
- **Unsplash**: Imagens de alta qualidade

## 📁 Estrutura do Projeto

```
sorriso-prime/
│
├── index.html              # Página principal
├── assets/
│   ├── css/
│   │   └── style.css      # Estilos do site
│   └── img/               # Imagens e favicons
│       ├── favicon.ico
│       ├── favicon-32x32.png
│       └── apple-touch-icon.png
│
└── README.md
```

## 🚀 Como Executar

1. Clone ou baixe este repositório:
```bash
git clone https://github.com/GuilhermeAnitelli/sorriso-prime.git
```

2. Navegue até a pasta do projeto:
```bash
cd sorriso-prime
```

3. Abra o arquivo `index.html` em seu navegador preferido ou use um servidor local:
```bash
# Com Python 3
python -m http.server 8000

# Com Node.js (http-server)
npx http-server
```

4. Acesse `http://localhost:8000` no navegador

## ⚙️ Configuração

### Formulário de Contato

O formulário está configurado para usar o Formspree. Para personalizar:

1. Acesse [Formspree](https://formspree.io/)
2. Crie uma conta e configure um novo formulário
3. Substitua o endpoint no arquivo `index.html`:
```html
<form action="https://formspree.io/f/SEU_CODIGO_AQUI" method="POST">
```

### Imagens e Favicons

Para personalizar os ícones e imagens:
- Adicione seus favicons na pasta `assets/img/`
- Atualize as URLs das imagens no arquivo `index.html`
- Recomendado: use suas próprias imagens para evitar dependência de serviços externos

### Meta Tags para SEO

Atualize as meta tags de Open Graph e Twitter no `<head>` para refletir suas informações:
```html
<meta property="og:image" content="URL_DA_SUA_IMAGEM">
<meta property="og:description" content="Sua descrição">
```

## 🎨 Personalização

### Cores e Estilos

Edite o arquivo `assets/css/style.css` para personalizar:
- Paleta de cores
- Tipografia
- Espaçamentos
- Breakpoints responsivos

### Conteúdo

Edite o arquivo `index.html` para alterar:
- Textos e descrições
- Serviços oferecidos
- Links de navegação
- Informações de contato

## 📱 Responsividade

O site foi desenvolvido com abordagem mobile-first e é totalmente responsivo, adaptando-se a:
- Smartphones (320px+)
- Tablets (768px+)
- Desktops (1024px+)

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:
1. Fazer um fork do projeto
2. Criar uma branch para sua feature (`git checkout -b feature/MinhaFeature`)
3. Commit suas mudanças (`git commit -m 'Adiciona nova feature'`)
4. Push para a branch (`git push origin feature/MinhaFeature`)
5. Abrir um Pull Request

## 📄 Licença

Este projeto está sob a licença MIT. Sinta-se livre para usar, modificar e distribuir.

## 👨‍💻 Autor

Desenvolvido por [Guilherme Anitelli](https://github.com/GuilhermeAnitelli)

---

⭐ Se este projeto foi útil para você, considere dar uma estrela no repositório!
