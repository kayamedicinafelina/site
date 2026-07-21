# Kaya Medicina Felina

Site institucional (one-page) da **Kaya Medicina Felina**, clínica veterinária exclusiva para gatos em Paranavaí, PR.

🔗 [kayamedicinafelina.github.io/site](https://kayamedicinafelina.github.io/site/)

## Sobre

Landing page estática com apresentação da clínica, diferenciais, história, serviços, horários/localização e formulário de agendamento que envia os dados via WhatsApp.

## Stack

Site estático — sem build, sem dependências, sem framework.

- HTML5 + CSS (inline no `index.html`)
- JavaScript vanilla (menu mobile, envio do formulário para WhatsApp, scroll suave)
- Fontes: [Cormorant Garamond](https://fonts.google.com/specimen/Cormorant+Garamond) e [DM Sans](https://fonts.google.com/specimen/DM+Sans) via Google Fonts
- [Google tag (gtag.js)](https://support.google.com/tagmanager) para conversão do Google Ads
- Dados estruturados `schema.org/VeterinaryCare` (JSON-LD)

## Estrutura

```
index.html          página única com todo o conteúdo, estilos e scripts
robots.txt           regras para crawlers + referência ao sitemap
sitemap.xml           sitemap XML
favicon-light.svg     favicon (tema claro)
favicon-dark.svg      favicon (tema escuro)
img/
  logo-topo.webp       logo usada no cabeçalho/hero
  logo-rodape.webp     logo usada no rodapé
  hero-gato.webp        foto do gato na seção hero
  og-image.jpg           imagem de compartilhamento (Open Graph / Twitter Card)
```

## Rodando localmente

Não há build. Basta servir os arquivos estáticos e abrir no navegador:

```bash
python -m http.server 8000
```

Depois acesse `http://localhost:8000/`.

## Deploy

Publicado via **GitHub Pages**, direto a partir da branch `main`. Qualquer push nela atualiza o site automaticamente.

## Contato

- WhatsApp: (44) 99174-1986
- E-mail: kayamedicinafelina@gmail.com
- Instagram: [@kaya.medicinafelina](https://www.instagram.com/kaya.medicinafelina/)
- Endereço: Rua Prudentópolis, 1514 — Jardim Ouro Branco, Paranavaí, PR
