# Solfie Estética Avançada e Saúde — Landing Page

Landing page responsiva para a clínica Solfie em Guarulhos/SP, preparada para receber tráfego do Google Ads e gerar conversas no WhatsApp.

**Repositório:** https://github.com/marceloterron2/sofieestetica

**Endereço do GitHub Pages:** https://marceloterron2.github.io/sofieestetica/

## Publicação

O workflow **Deploy Solfie no GitHub Pages** configura e publica o site no GitHub Pages em alterações na branch main. Se o site ainda não estiver ativo, abra **Settings → Pages → Build and deployment → Source: GitHub Actions** e execute o workflow na guia Actions.

## Confirmações antes dos anúncios

- **WhatsApp:** o telefone público de diretórios da Solfie é (11) 97313-8202. Confirmar com a Priscila antes de veicular. Atualizar o número no `script.js`, nos links de fallback e no JSON-LD se houver mudança.
- **Endereço:** Rua Otávio Forghieri, 204, sala 106, Jardim Gumercindo, Guarulhos. Confirmar endereço atual.
- **Fotos e logo:** fotografias ilustrativas licenciadas no Unsplash; não são fotos da clínica nem demonstração de resultados. O logotipo atual é uma representação tipográfica; substituir pelo original quando disponível.
- **Google Ads:** não há ID de conversão, Google Tag Manager, GA4 ou pixel instalado. Os cliques nos links do WhatsApp geram apenas o evento `solfie_whatsapp_click` no `dataLayer`. Configurar tags reais e testar antes da campanha. Não confundir clique em WhatsApp com compra.
- **LGPD:** atualizar a Política de Privacidade e controles de consentimento quando forem ativados rastreadores publicitários.
- **Serviços:** confirmar nomes dos procedimentos e textos com a clínica.

## Arquivos

`index.html`, `style.css`, `script.js`, `privacidade.html`, `favicon.svg`, `robots.txt`, `sitemap.xml`, `.nojekyll` e `.github/workflows/deploy-pages.yml`.

## Créditos das imagens ilustrativas

- Rany Lops, Unsplash: https://unsplash.com/photos/a-woman-with-her-hand-on-her-face-CrLkgK1DhoI
- Luiz Rogério Nunes, Unsplash: https://unsplash.com/photos/a-woman-is-getting-her-face-cream-applied-qdjUs4QwJf0

Site estático sem backend nem armazenamento próprio de leads.