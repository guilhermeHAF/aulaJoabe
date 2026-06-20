# Site League of Legends - Guilherme Henrique

Site educacional sobre League of Legends, desenvolvido para a disciplina Tecnologias para Internet (UNIUBE).

## Estrutura do Projeto

```
site joabe/
├── index.html          # Página inicial
├── pages/              # Páginas internas
├── css/style.css       # Estilos responsivos
├── js/main.js          # Menu hamburger e interações
├── img/                # Imagens
├── assets/             # Favicon e recursos
├── robots.txt
└── sitemap.xml
```

## Google Search Console

### Como cadastrar o site

1. Acesse [Google Search Console](https://search.google.com/search-console).
2. Clique em **Adicionar propriedade** e informe a URL do site publicado.
3. Escolha o método de verificação **Tag HTML**.
4. Copie o código fornecido (ex.: `content="abc123..."`).
5. Em cada página HTML, descomente e preencha a meta tag no `<head>`:

```html
<meta name="google-site-verification" content="SEU_CODIGO_AQUI" />
```

### Como verificar o site

1. Após inserir a meta tag, publique o site.
2. Volte ao Search Console e clique em **Verificar**.
3. Aguarde a confirmação de propriedade verificada.

### Como enviar o sitemap

1. No Search Console, acesse **Sitemaps** no menu lateral.
2. Informe a URL do sitemap: `https://SEU-DOMINIO/sitemap.xml`
3. Clique em **Enviar**.

> **Importante:** Substitua `SEU-DOMINIO` em `robots.txt`, `sitemap.xml` e nos comentários do projeto pelo domínio real (ex.: GitHub Pages).

## Google Analytics GA4

1. Crie uma propriedade em [Google Analytics](https://analytics.google.com/).
2. Copie o **Measurement ID** (formato `G-XXXXXXXXXX`).
3. Em cada página HTML, descomente o bloco GA4 no `<head>` e substitua `G-XXXXXXXXXX` pelo seu ID.

## Autor

- **Aluno:** Guilherme Henrique
- **RA:** 5167654
- **Instituição:** UNIUBE
